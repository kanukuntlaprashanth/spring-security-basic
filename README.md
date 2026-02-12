# spring-security-basic
# Project 1: Basic Authentication with Spring Security

## Overview

This project demonstrates **HTTP Basic Authentication** using **Spring Boot** and **Spring Security**.  
It is a simple, stateless authentication mechanism where:

- Users send credentials (username and password) in every request.
- Spring Security validates credentials and stores the authenticated user temporarily in `SecurityContext`.
- Role-based authorization controls access to endpoints.
---

## Features

- HTTP Basic Authentication
- In-memory user storage with custom roles
- Role-based access control
- Custom security configuration using `SecurityFilterChain`
- Stateless authentication (no sessions)
- Endpoint-level authorization
- Password hashing using `BCryptPasswordEncoder`

---

## Technologies Used

- **Java 17+**
- **Spring Boot 3.x**
- **Spring Security**
- **Maven / Gradle**
- **IntelliJ IDEA** 
- **REST endpoints** for testing

---

## Project Structure
src
└─ main
├─ java
│ └─ com.example.basicauth
│ ├─ config # Security configuration
│ ├─ controller # REST controllers
└─ resources
└─ application.properties

## How to Run

1. Clone the repository:

git clone https://github.com/<username>/spring-security-basic.git
cd spring-security-basic

2. Build and run using Maven:
mvn clean spring-boot:run

## License

This project is licensed under the MIT License.
