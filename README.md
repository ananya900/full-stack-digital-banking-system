# Full Stack Digital Banking System

A production-style full-stack digital banking platform built using Spring Boot, MySQL, and React.
The system simulates real-world banking operations such as account management, transactions, loan processing, and beneficiary management.

---

## Tech Stack

Backend
- Java 17
- Spring Boot
- Spring Data JPA
- Hibernate
- Maven
- MySQL
- Swagger OpenAPI

Frontend
- React
- Bootstrap / Material UI
- TypeScript / JavaScript
- REST API Integration

Tools
- Git & GitHub
- Postman
- Swagger UI
- Docker (optional)

---

## Core Features

Customer
- Register / Login
- Open bank accounts
- Deposit, withdraw, and transfer funds
- View transaction history
- Add beneficiaries
- Apply for loans

Employee
- Review transactions
- Approve or reject loan applications
- Monitor customer accounts

Admin
- Manage users and employees
- Generate system reports

---

## System Architecture

Frontend (React)
↓
Spring Boot REST API
↓
Service Layer
↓
Repository Layer (JPA)
↓
MySQL Database

---

## API Documentation

Swagger UI available at:
http://localhost:9090/swagger-ui.html

Base API URL:
http://localhost:9090

---

## Running the Backend

1. Clone repository
git clone https://github.com/ananya900/full-stack-digital-banking-system.git

2. Configure database in:
src/main/resources/application.properties

3. Build project
mvn clean install

4. Run application
mvn spring-boot:run

Backend will start at:
http://localhost:9090

---

## Project Structure

full-stack-digital-banking-system
│
├── backend
│   ├── controller
│   ├── service
│   ├── repository
│   ├── entity
│   └── config
│
├── frontend
│   └── react-app
│
└── docs

---

## Author

Ananya G N
Information Science Engineering Student
Focused on Backend Development, Java, and Full Stack Systems
