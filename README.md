# BloodLink 🩸

**Connecting donors. Supporting families. Saving lives.**

BloodLink is a full-stack blood donation coordination platform designed to connect individuals seeking blood donors with potential donors and authorized healthcare organizations.

The platform aims to centralize blood donation requests, making them easier to discover, verify, manage and respond to.

> 🚧 **Status:** Currently under development.

## 🎯 Project Overview

Blood donation requests are frequently shared through social media platforms and messaging applications. However, these requests can become difficult to track, reach the right audience or manage effectively.

BloodLink aims to address this problem by providing a centralized platform where:

- Individuals and families can submit blood donation requests.
- Healthcare organizations can publish donation requests.
- Potential donors can discover requests based on blood type and location.
- Donors can express interest in helping.
- Requesters can monitor donor responses.
- Administrators can review and verify requests before publication.

## ✨ Planned Features

### For Donors
- User registration and authentication.
- Personalized donor profiles.
- Blood type and location preferences.
- Browse active blood donation requests.
- Filter requests by blood type and location.
- Express interest in donation requests.
- Track previous responses.

### For Requesters
- Submit blood donation requests on behalf of patients.
- Provide hospital and donation details.
- Track request verification status.
- Monitor donor responses.
- Manage and close submitted requests.

### For Healthcare Organizations
- Organization registration and verification.
- Submit and manage blood donation requests.
- Provide hospital verification information.

### For Administrators
- Review and verify donation requests.
- Approve or reject submitted requests.
- Verify healthcare organizations.
- Manage users and platform activity.
- Monitor request statuses.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| React | Frontend development |
| TypeScript | Type safety |
| Bootstrap 5 | Responsive UI components and styling |
| Python | Backend development |
| FastAPI | REST API |
| PostgreSQL | Relational database |
| Git & GitHub | Version control |

**Planned cloud deployment:** Amazon Web Services (AWS).

## 🏗️ Architecture

BloodLink follows a client-server architecture.

```text
             BloodLink
                 |
        React + TypeScript
                 |
          REST API (HTTP)
                 |
          Python FastAPI
                 |
             PostgreSQL
```

## 🔐 Security and Privacy

Security and privacy are important considerations throughout development.

Planned considerations include:

- Secure password hashing.
- Authentication and role-based authorization.
- Input validation and error handling.
- Restricted access to sensitive information.
- Hospital and organization verification.
- Administrative audit logs.

BloodLink is intended as a donation coordination platform, not a medical decision-making system. Donor eligibility and blood compatibility must be confirmed by authorized healthcare professionals.

## 🚀 Getting Started

Installation and setup instructions will be added as the application development progresses.

### Prerequisites

- Node.js and npm
- Python
- PostgreSQL
- Git

## 📌 Development Roadmap

- [ ] Requirements analysis and project planning
- [ ] UI foundation and responsive layout
- [ ] React frontend setup
- [ ] FastAPI backend setup
- [ ] PostgreSQL database design and integration
- [ ] User authentication and authorization
- [ ] Donor profile management
- [ ] Blood donation request management
- [ ] Request verification workflow
- [ ] Donor response management
- [ ] Donor and requester dashboards
- [ ] Administrative dashboard
- [ ] Testing and security improvements
- [ ] AWS deployment

## 🌱 Future Enhancements

Potential future improvements include:

- Email and real-time notifications.
- Interactive donation centre maps.
- Arabic and English language support.
- Advanced request filtering.
- Hospital integration.
- Platform analytics.

## 👩‍💻 Author

Developed as an independent full-stack software development project.

## 📄 License

License to be determined.