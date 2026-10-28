# Smart Campus Recruitment & Interview Scheduler

A web-based college placement management system designed to simplify campus recruitment activities, manage placement drives, coordinate interview schedules, and help students prepare for career opportunities.

The platform provides a centralized solution for managing recruitment rounds, tracking student performance, and organizing interview schedules efficiently.

## Overview

The **Smart Campus Recruitment & Interview Scheduler** is a collaborative academic project developed to improve the efficiency of college placement and recruitment activities.

The system helps placement teams manage recruitment drives, coordinate interview rounds, organize student information, and streamline communication between students, placement coordinators, and recruiters.

## Key Features

- **Student Management** — Organize student information and placement-related records.
- **Recruitment Drive Management** — Manage company recruitment activities and placement drives.
- **Interview Scheduling** — Coordinate interview rounds and organize schedules.
- **Clash-Free Scheduling** — Support efficient interview scheduling to reduce scheduling conflicts.
- **Round-Wise Progress Tracking** — Track recruitment progress across different interview rounds.
- **Marks Management** — Upload and manage marks for individual recruitment rounds.
- **Department-Based Results** — Organize and view results according to departments.
- **Company-Wise Progress** — Monitor recruitment progress for different companies.
- **Centralized Dashboard** — Access recruitment-related information in one place.
- **Email Notifications** — Support email communication for relevant recruitment activities.

*Note: Feature availability depends on the current implementation and configuration of the application.*

## Technology Stack

### Frontend
- React.js
- JavaScript
- HTML5
- CSS3
- Vite

### Backend
- Java
- Spring Boot
- Spring Data JPA

### Database
- MongoDB

### Tools and Platforms
- Git and GitHub
- Maven
- Visual Studio Code
- Render / other configured deployment services

## Project Structure

```text
smart-campus-recruitment-scheduler/
│
├── backend/
│   ├── src/
│   ├── pom.xml
│   └── Dockerfile
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── constants/
│   │   ├── context/
│   │   ├── pages/
│   │   ├── routes/
│   │   └── services/
│   ├── package.json
│   └── vite.config.js
│
└── README.md
```

## Getting Started

Follow the instructions below to run the project locally.

### Prerequisites

Install the following software before starting:

- Java Development Kit (JDK 21 or the version required by the backend)
- Node.js and npm
- Maven, or use the Maven Wrapper if available
- MongoDB or access to a configured MongoDB database
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/Gangadhar8080/smart-campus-recruitment-scheduler.git
cd smart-campus-recruitment-scheduler
```

### 2. Configure the Backend

Open a terminal and navigate to the backend directory.

```bash
cd backend
```

Configure the required database connection, email settings, and other environment variables using the application's configuration files or environment settings.

Do not commit database passwords, API keys, JWT secrets, or email credentials to GitHub.

Start the backend using Maven:

```bash
mvn spring-boot:run
```

If Maven is not installed globally, use the Maven Wrapper if the project includes it.

### 3. Configure the Frontend

Open another terminal from the project root.

```bash
cd frontend
npm install
npm run dev
```

Open the local URL displayed in the terminal to access the frontend.

### 4. Configure Environment Variables

The application may require environment variables for database connectivity, backend API URLs, authentication, and email delivery.

Refer to the existing configuration files and deployment settings to identify the exact variables required by your version of the project.

Use a local `.env` file or your deployment platform's environment-variable settings where appropriate. Never publish sensitive credentials.

## Deployment

The application has been developed for web-based access, with frontend and backend deployment configured according to the project environment.

For the existing live application, use the deployment URL provided by the project team.

**Live Demo:** Add your verified application URL here.

**GitHub Repository:** [Smart Campus Recruitment & Interview Scheduler](https://github.com/Gangadhar8080/smart-campus-recruitment-scheduler)

## Learning Outcomes

Through this project, the team gained practical experience in:

- Developing a web application using React and Spring Boot.
- Integrating frontend and backend components.
- Working with database operations and application configuration.
- Managing recruitment workflows and interview-round progression.
- Collaborating through Git and GitHub.
- Understanding application deployment and maintenance.

## Future Enhancements

- Automated interview reminders and notifications.
- Calendar integration for interview schedules.
- Advanced recruitment analytics and reports.
- Improved role-based access control.
- Enhanced student placement dashboards.
- Exportable recruitment reports.

## Project Information

**Project Name:** Smart Campus Recruitment & Interview Scheduler

**Project Type:** Academic / Collaborative Project

**Domain:** Campus Placement Management

**Repository Owner:** Gangadhar8080

**Contributors:** Developed collaboratively. Refer to the repository's contributors and commit history for individual contributions.

## License

No license has been specified for this repository yet. Please add an appropriate license if you intend to distribute or reuse the project under specific terms.

