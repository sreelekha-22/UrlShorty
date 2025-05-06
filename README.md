# UrlShorty 🔗
A backend-only custom URL Shortener built with Spring Boot.

## 📌 Overview
**UrlShorty** is a personal project that provides RESTful APIs to shorten URLs, manage users with JWT-based authentication, and secure access using Spring Security. All endpoints were tested using Postman.

## 🛠️ Tech Stack
- Java 21
- Spring Boot
- Spring Security
- Spring Data JPA (Hibernate)
- JWT (JSON Web Tokens)
- MySQL 
- Maven

## 🚀 Features
- Shorten and redirect long URLs
- User registration and login
- JWT-based authentication
- Role-based access control
- Secure API endpoints

## 🧪 Testing
All endpoints tested using **Postman**.  
Authorization is handled by passing the JWT token in the `Authorization` header:

## 📂 API Endpoints 
| Method | Endpoint                 | Description                     |
|--------|--------------------------|---------------------------------|
| POST   | /api/auth/public/register| Register a new user             |
| POST   | /api/auth/public/login   | Login and get JWT token         |
| POST   | /api/urls/shorten        | Shorten a long URL              |
| GET    | /api/urls/myurls         | View all user's shortened URLs  |
| GET    | /api/urls/analytics      | URL analytics for a specific URL|
| GET    | /api/urls/totalClicks    | View total clicks analytics     |
