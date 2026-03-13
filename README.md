# Maverick Bank – Full Stack Digital Banking System

A production-style **full-stack digital banking platform** built with **Spring Boot, MySQL, and Angular/React frontend**.
The system simulates real banking operations such as account management, transactions, loan processing, and beneficiary management.

---

## Tech Stack

**Backend**

* Java 17
* Spring Boot
* Spring Data JPA
* Hibernate
* Maven
* MySQL
* Swagger OpenAPI

**Frontend**

* Angular (recommended) or React
* Angular Material / Bootstrap
* TypeScript
* REST API integration

**Tools**

* Git & GitHub
* Postman
* Swagger UI
* Docker (optional)

---

## Core Features

### Customer

* Register / Login
* Open Bank Accounts
* Deposit / Withdraw / Transfer funds
* View Transaction History
* Add Beneficiaries
* Apply for Loans

### Employee

* Review transactions
* Approve or reject loan applications
* Monitor accounts

### Admin

* Manage users
* Manage employees
* System reporting

---

## System Architecture

Frontend (Angular / React)
⬇
Spring Boot REST API
⬇
Service Layer
⬇
Repository Layer (JPA)
⬇
MySQL Database

---

## API Documentation

Swagger UI available at:

```
http://localhost:9090/swagger-ui.html
```

Base API URL:

```
http://localhost:9090
```

---

## Running the Backend

1. Clone repository

```
git clone https://github.com/ananya900/full-stack-digital-banking-system.git
```

2. Configure database in:

```
src/main/resources/application.properties
```

3. Build project

```
mvn clean install
```

4. Run application

```
mvn spring-boot:run
```

Backend will start at:

```
http://localhost:9090
```

---

## Project Structure

```
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
```

---

## Author

**Ananya G N**
Information Science Engineering Student
Focused on **Backend Development, Java, and Full Stack Systems**
