# Employee Management System
- FullStack Java Project
## Overview
The **Employee Management System** is a Spring Boot application that provides functionalities for user registration, employee management, and administrative tasks. Admins can register users and employees, and employees can log in and access their personal details.

## Features
- Admin can register users with company email and password.
- Employees can log in and view their details.
- Admin can manage employee information (create, view, update, delete).
- **Role-based access:** Admin and User roles.
- Secure password handling with encryption.
- **Role Management:** Allow admins to assign and manage roles for different users.
- **Employee Projects:** Track and manage projects for employees.
  
## Technologies Used
- **Java 17**
- **Spring Boot** (Web, Security, JPA)
- **Spring Data JPA** with Hibernate
- **Thymeleaf** for server-side rendering
- **MySQL Database** for database services
- **Spring Security** for authentication and authorization 
- **BCrypt** is used to encode and store passwords securely.
- **IDE** can be used **Eclipse, VS code, IntellIj**

## Project Structure

```bash
src/
├── main/
│   ├── java/com/excelr/
│   │   ├── controller/           # Controllers for handling HTTP requests
│   │   ├── DTO/                  # Data Transfer Objects
│   │   ├── model/                # Entity classes (User, Employee)
│   │   ├── repository/           # JPA Repositories for database interaction
│   │   ├── service/              # Business logic and service layer
│   │   └── config/               # Security and email configurations
│   └── resources/
│       ├── templates/            # Thymeleaf templates (HTML pages)
│       ├── application.properties # Application configuration
│       └── static/               # Static files (CSS, JS)
└── test/
    └── java/com/excelr/          # Unit and integration tests
