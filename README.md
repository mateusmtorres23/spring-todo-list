# Spring Todo List

A simple task management API developed as a learning project to practice backend development with Java and Spring Boot.

## Technologies

- Java
- Spring Boot
- Spring MVC
- Spring Data JPA
- PostgreSQL
- BCrypt
- OpenAPI
- Docker

## Architecture

The application is organized into separate layers for:

- Controllers
- Services
- Repositories
- DTOs
- Domain models

PostgreSQL is used for persistence through Spring Data JPA, and Docker Compose is available to run both the application and database.

## Features

- User registration
- Password hashing with BCrypt
- Task creation
- User-associated tasks
- Basic authentication for task operations
