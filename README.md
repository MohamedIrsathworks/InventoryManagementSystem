# Inventory Management System – Backend

This project is a **backend-only** implementation of an Inventory Management System developed using **Spring Boot** and **Maven**. It provides a set of RESTful APIs to perform standard inventory operations and can be easily integrated with a frontend or other systems.

## Features

- **CRUD Operations**: Create, Read, Update, and Delete inventory items via API.
- **Spring Security (if applicable)**: Optionally included for securing endpoints.
- **Postman API Integration**: All endpoints tested using Postman.
- **Thymeleaf Controllers**: Used for basic routing or template rendering (if enabled).

## Technologies Used

- **Spring Boot** – Core framework for building the backend
- **Maven** – For dependency management and project configuration
- **Spring MVC** – For building RESTful web services
- **Thymeleaf** – Template engine (optional/basic usage)
- **SQL/Database** – (Add this if you're connecting to a database like MySQL or H2)

## How to Run

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd inventory-management-system

2. **Build the project** - mvn clean install
3. **Run the application** -mvn spring-boot:run

Access the API by Opening your Postman and go to: **http://localhost:8080/**

**Sample API Endpoints**
GET /items – Retrieve all inventory items
POST /items – Add a new item
PUT /items/{id} – Update an existing item
DELETE /items/{id} – Delete an item
