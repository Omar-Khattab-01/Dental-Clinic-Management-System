# Dental Clinic Management System (DCMS)

A full-stack web application built with **Spring Boot** and **Maven** to manage dental clinic operations such as patients, appointments, staff, and treatments. This project demonstrates relational database design, SQL-backed CRUD flows, and a clean MVC architecture.

---

## Features
- Patient registration and management
- Appointment scheduling and viewing
- Employee and branch management
- Treatment tracking
- User authentication
- Server-side rendered UI using templates (Thymeleaf)

---

## Tech Stack
- **Backend:** Java, Spring Boot
- **Build:** Maven
- **Database:** SQL (JDBC / RowMappers)
- **Frontend:** Thymeleaf, HTML, CSS
- **Architecture:** MVC

---

## Project Structure

src/main/java/com/dcms/dcms
├── controllers # Web routes & request handling
├── models # Domain models
├── mappers # SQL RowMappers
└── DcmsApplication.java

src/main/resources
├── templates # Thymeleaf views
└── static/css # Styles


---

## How to Run

### Requirements
- Java 11+
- Maven
- A SQL database (configured in `application.properties`)

### Setup
1) Configure your DB credentials in:

src/main/resources/application.properties


2) Run the application:
```bash
mvn spring-boot:run

3) Open in browser:

http://localhost:8080