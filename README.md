# Bookify

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
    - [Backend (bookify)](#backend-bookify)
    - [Frontend (bookify-ui)](#frontend-bookify-ui)
- [Getting Started](#getting-started)

## Overview

Bookify is a web application for book enthusiasts to manage collections, share books, and connect with others. It features secure user registration, book management, and a borrowing system with approval workflows, built using Spring Boot, Angular, and JWT for authentication.

## Features

- **User Accounts**: Supports new user sign-up with email verification and secure login for existing users.  
- **Book Collection Management**: Allows users to manage their library by adding, updating, sharing, or archiving books.  
- **Borrow and Return System**: Enables book borrowing, tracks availability, and includes return approval mechanisms.  
- **Secure Access**: Ensures user authentication and data safety using JWT-based token systems.

#### Class Diagram
![Class Diagram](screenshots/class-diagram.png)

#### Spring Security Workflow
![Security Diagram](screenshots/security.png)

## Technologies Used

### Backend (bookify)

- Spring Boot (version 3)
- Spring Security (version 6)
- JWT-based Authentication
- Hibernate with Spring Data JPA
- Validation using JSR-303
- API Documentation via Swagger/OpenAPI
- Dockerized Services
- CI/CD with GitHub Actions
- Keycloak Integration for User Management

### Frontend (bookify-ui)

- Angular Framework
- Modular and Lazy Loading Architecture
- Route Guards for Authentication
- API Integration with OpenAPI Generator
- User Interface Styled with Bootstrap

## Getting Started

To set up and run the application locally, refer to the setup guides provided in the respective project directories:

- [Backend Setup Guide](/bookify/README.md)  
- [Frontend Setup Guide](bookify-ui/README.md)
