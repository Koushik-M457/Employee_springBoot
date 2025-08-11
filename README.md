# Employee_springBoot
# Employee Management System

## Overview

This project is a comprehensive **Employee Management System** built using **Spring Boot**, **Java 17**, and **Maven**. It provides a RESTful API to manage employee records, supporting all basic CRUD (Create, Read, Update, Delete) operations.

## Features

- **CRUD Operations**: Manage employee data with endpoints for creating, reading, updating, and deleting records.
- **Database Integration**: Utilizes **MySQL** for persistent storage of employee information.
- **RESTful API**: Exposes endpoints for seamless integration with front-end applications or other services.
- **Authentication**: Implements basic authentication for secure access to the API.

## Technologies Used

- **Backend**: Spring Boot, Java 17
- **Database**: MySQL
- **Build Tool**: Maven
- **API Testing**: Postman (for testing endpoints)

## Setup Instructions

### Prerequisites

- **Java 17** or higher
- **Maven** 3.8.1 or higher
- **MySQL** database server

### Clone the Repository

```bash
git clone https://github.com/Koushik-M457/Employee_springBoot.git
cd Employee_springBoot
```
Build and Run the Application

mvn clean install
mvn spring-boot:run
The application will start on http://localhost:8081.

API Endpoints
Employee Endpoints
GET /api/employees: Retrieve all employees.

GET /api/employees/{id}: Retrieve a specific employee by ID.

POST /api/employees: Create a new employee.

PUT /api/employees/{id}: Update an existing employee.

DELETE /api/employees/{id}: Delete an employee by ID.

UI Inferface:

<img width="1920" height="684" alt="image" src="https://github.com/user-attachments/assets/668254bc-44ba-42a1-8b2a-8550ce57df66" />


