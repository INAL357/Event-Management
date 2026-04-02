# Event Management System (Backend)

## Overview

This project is a backend system for an Event Management platform built using Spring Boot. It provides secure and scalable REST APIs for managing users, events, and bookings, with support for role-based access control.

---

## Features

* User authentication and authorization
* Role-based access control (Admin, Organizer, User)
* Event creation, update, and deletion (Admin)
* Event booking system
* Booking management and tracking
* RESTful API design

---

## Tech Stack

* Backend: Spring Boot, Java
* Database: MySQL 
* Security: Spring Security (JWT if implemented)
* Build Tool: Maven

---

## Architecture

The application follows a layered architecture:

Controller → Service → Repository → Database

---

## Project Structure

```
src/main/java/com/app/event/
 ├── controller
 ├── service
 ├── repository
 ├── entities
 ├── exception
 ├── security
 ├── dto
 ├── config
 
```

---

## Core Modules

- User Module: Handles registration, login, and role management  
- Event Module: Manages event creation and updates  
- Booking Module: Handles event reservations and tracking  
- Payment Module: Will handle secure payment processing for event bookings  

---

## How to Run

1. Clone the repository
2. Navigate to the project directory
3. Run the application:

```
mvn spring-boot:run
```

---

## API Endpoints (Sample)

* POST /api/auth/register
* POST /api/auth/login
* POST /api/events
* GET /api/events
* POST /api/bookings

---

## Future Enhancements

- React frontend integration  
- Payment gateway integration (Razorpay / Stripe)  
- Secure transaction handling  
- Email notifications  
- Admin dashboard

---

## Author

Inal Mendonca
