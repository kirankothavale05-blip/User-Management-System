# User Management System

A full-stack User Management System built using Spring Boot, React.js, MySQL, Java 17, Maven, Hibernate, and REST APIs. The application provides complete CRUD (Create, Read, Update, Delete) functionality for managing user records through a responsive and user-friendly interface.

## Features

- Add new users
- View all users
- View user details
- Update existing user details
- Delete users
- Responsive user interface
- RESTful API integration
- MySQL database connectivity
- Exception handling and validation

## Tech Stack

### Frontend
- React.js
- React Router DOM
- Axios
- Bootstrap

### Backend
- Spring Boot
- Spring Data JPA
- Hibernate
- REST APIs

### Database
- MySQL

### Tools & Technologies
- Java 17
- Maven
- Git & GitHub
- VS Code
- Postman

## Project Architecture

```text
User Interface (React)
          ↓
REST API (Spring Boot)
          ↓
Controller Layer
          ↓
Service Layer
          ↓
Repository Layer (JPA)
          ↓
MySQL Database
```

## API Endpoints

| Method | Endpoint | Description |
|----------|----------|-------------|
| GET | /users | Get all users |
| GET | /user/{id} | Get user by ID |
| POST | /user | Add a new user |
| PUT | /user/{id} | Update user details |
| DELETE | /user/{id} | Delete user |

## Installation & Setup

### Clone Repository

```bash
git clone https://github.com/kirankothavale05-blip/User-Management-System.git
```

### Backend Setup

1. Open the Spring Boot project.
2. Configure MySQL database in `application.properties`.

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/userdb
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

3. Run the Spring Boot application.

```bash
mvn spring-boot:run
```

Backend API will start at:

```text
http://localhost:8080
```

### Frontend Setup

```bash
cd user-frontend
npm install
npm start
```

Frontend application will start at:

```text
http://localhost:3000
```

Backend API:

```text
http://localhost:8080
```

## Screenshots

### Home Page
<img width="1907" height="237" alt="image" src="https://github.com/user-attachments/assets/9645f23e-bbd8-45fd-b872-1dc479082dc8" />

### Add User
<img width="1912" height="690" alt="Screenshot 2026-06-18 203247" src="https://github.com/user-attachments/assets/a8784f45-c19e-4175-9d04-df475bc0eaa7" />

### User List
<img width="1881" height="516" alt="Screenshot 2026-06-18 082523" src="https://github.com/user-attachments/assets/50eb04ee-4696-47dd-b173-4d03f4f40b5c" />


## Future Enhancements

- User Authentication & Authorization
- JWT Security
- Search and Filter Functionality
- Pagination
- Role-Based Access Control
- Docker Deployment
- Cloud Deployment (AWS)

## Learning Outcomes

Through this project, I gained hands-on experience with:

- Building REST APIs using Spring Boot
- React Component Development
- API Integration using Axios
- Database Integration with MySQL
- CRUD Operations
- Hibernate and JPA
- Maven Build Management
- API Testing using Postman
- Git and GitHub Version Control
- Full Stack Application Development

## Author

**Kiran Kothavale**

Java Full Stack Developer

GitHub: https://github.com/kirankothavale05-blip

## About

A Full Stack User Management System built using Spring Boot, React.js, MySQL, Hibernate, Java 17, Maven, REST APIs, and Postman. The application supports CRUD operations including adding, viewing, updating, and deleting users through a responsive frontend and robust backend architecture.
