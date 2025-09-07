# Employee Management System API

A RESTful API for managing employees, built with **Java Spring Boot** and **MySQL**.

## Features
- Create, Read, Update, Delete (CRUD) employee records
- REST endpoints for employee management
- MySQL database integration

## Tech Stack
- Java 17
- Spring Boot
- Spring Data JPA
- MySQL
- Maven

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/sannal123/employee-management-system.git
Configure MySQL database in application.properties.

Build and run the project:

bash
Copy code
mvn clean install
mvn spring-boot:run
Test APIs using Postman or any API client.

Endpoints
GET /employees - List all employees

GET /employees/{id} - Get employee by ID

POST /employees - Add a new employee

PUT /employees/{id} - Update employee

DELETE /employees/{id} - Delete employee

Author
Sannal Yadav
