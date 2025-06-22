# Team Roles

## Backend Developer
Responsible for building and maintaining the server-side of the application. Handles business logic, database interaction, APIs, and integrates third-party services.

## Frontend Developer
Develops the client-side of the application using modern JavaScript frameworks. Focuses on creating responsive, interactive user interfaces.

## Full Stack Developer
Works across both frontend and backend. Bridges the gap between UI design and backend services, ensuring seamless data flow and functionality.

## UI/UX Designer
Designs user-friendly interfaces and experiences. Creates wireframes, prototypes, and ensures the app is intuitive and accessible for users.

## Project Manager
Coordinates the team, sets timelines, manages deliverables, and communicates with stakeholders. Ensures the project stays on scope, budget, and schedule.

---

# Technology Stack

## Django
A high-level Python web framework used for building the backend, including models, views, and APIs. Offers built-in admin and security features.

## PostgreSQL
A powerful, open-source object-relational database used to store structured data securely with advanced querying and indexing capabilities.

## Docker
Used for containerizing the application to ensure consistency across development, staging, and production environments.

---

# Database Design

## Users
Stores user information including login credentials, profile data, and roles (e.g., guest, host, admin).

## Properties
Contains listings or rental units created by users, including descriptions, location, pricing, and availability.

## Reviews
Captures user-generated feedback for properties, including ratings and comments.

## Bookings
Stores data about property reservations, including check-in/check-out dates, user ID, property ID, and status.

## Payments
Manages transaction data such as amount, payment method, payment status, and reference to bookings.

---

# Feature Breakdown

## User Management
Handles registration, login, password reset, profile updates, and user roles/permissions.

## Property Management
Allows hosts to create, edit, and delete property listings. Supports image uploads, pricing, and availability settings.

## Booking System
Enables users to search for properties, book available dates, view their reservations, and cancel if needed.

---

# API Security

## Authentication
Ensures that only registered users can access secure endpoints using token-based or session-based authentication.

## Authorization
Controls access based on user roles. For example, only property owners can modify their listings.

## Rate Limiting
Protects the API from abuse and denial-of-service attacks by limiting the number of requests a user can make in a given time period.

---

# CI/CD Pipeline

## GitHub Actions
Automates workflows like testing, building, and deploying the app every time code is pushed to the repository.

## Docker
Used in the pipeline to build application containers and deploy them to testing or production environments with consistent configurations.
