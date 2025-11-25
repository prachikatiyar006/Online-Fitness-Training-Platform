# Online Fitness Training Platform

## Overview
The **Online Fitness Training Platform** is a web application that allows users to access workout plans, track their progress, and interact with trainers. Administrators manage users, trainers, and content. The platform is built using **Spring Boot** for the backend and **React.js** for the frontend.

---

## Features

### User
- View available workout plans.
- Track fitness progress with entries and statistics.
- Communicate with trainers.
- Secure login and authentication.

### Trainer
- Create and manage workout plans.
- View and monitor user progress.
- Interact with users via messages.

### Admin
- Manage users and trainers.
- Oversee workout content.
- Dashboard with analytics and system monitoring.

---

## Technology Stack

- **Backend:** Java, Spring Boot, Maven
- **Frontend:** React.js, Vite, Tailwind CSS
- **Database:** MySQL
- **Build Tools:** Maven
- **Version Control:** Git

---

## Project Structure

Online Fitness Training Platform/
│
├── backend/ # Spring Boot backend
│ └── src/main/java/com/example/fitness/
│ ├── config/ # Security configurations
│ ├── controller/ # REST controllers
│ ├── dto/ # Data transfer objects
│ ├── model/ # Entities and models
│ ├── repository/ # Spring Data JPA repositories
│ └── service/ # Business logic services
│
├── frontend/ # React frontend
│ ├── public/ # HTML files
│ ├── src/
│ ├── components/ # React components
│ ├── pages/ # React pages
│ ├── api.js # API calls
│ └── App.jsx # Root component
│
├── pom.xml # Maven build file for backend
├── package.json # Node.js dependencies for frontend
└── README.md # Project documentation

yaml
Copy code

---

## Prerequisites

- Java 17
- Maven 3.9+
- Node.js 18+
- MySQL 8+
- Git

---

## Backend Setup

1. Clone the repository:

```bash
git clone <repository-url>
cd "Online Fitness Training Platform/backend"
Configure MySQL database in application.properties:

properties
Copy code
spring.datasource.url=jdbc:mysql://localhost:3306/fitness_db
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
Install dependencies and build:

bash
Copy code
mvn clean install
Run the backend:

bash
Copy code
mvn spring-boot:run
Backend will run on http://localhost:8080.

Frontend Setup
Navigate to frontend:

bash
Copy code
cd "../frontend"
Install dependencies:

bash
Copy code
npm install
Start development server:

bash
Copy code
npm run dev
Frontend will run on http://localhost:5173 (or as shown in terminal).

Running the Full Project
Start MySQL service.

Start backend server (mvn spring-boot:run).

Start frontend server (npm run dev).

Open browser at the frontend URL and login/register.

Notes
Make sure the backend URL matches in frontend/src/api.js.

Use Postman or Swagger to test API endpoints if needed.

The project is structured to allow adding more modules like nutrition plans, AI-based progress analysis, and video sessions.

Contribution
Fork the repository.

Create a new branch for your feature/bug fix.

Commit changes with clear messages.

Push and create a Pull Request.

License
MIT License. See LICENSE for details.

Contact
Project Maintainer: Prachi katiyar 

Email: prachikatiyar001@gmail.com

yaml
Copy code

---

If you want, I can also make a **short, clean version** suitable for GitHub that looks more appealing with badges and quick-start instructions.  

Do you want me to create that GitHub-ready version as well?
