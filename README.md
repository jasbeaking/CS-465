# CS-465
Full Stack Development
# Travlr Getaways Full Stack Web Application

## Overview
**Travlr Getaways** is a full stack travel booking web application built using the **MEAN stack** (*MongoDB, Express, Angular, Node.js*).

The application provides:
- A customer-facing booking platform for browsing and managing trips  
- A secure admin dashboard (SPA) for managing trips and customer data  

---

## Architecture

### Frontend

#### Customer-Facing Application
- Built with Express, Handlebars templates, and JavaScript
- Follows a multi-page application (MPA) structure
- Delivers dynamic content while maintaining a traditional browsing experience  

#### Admin Dashboard
- Built as a Single Page Application (SPA) using Angular
- Supports:
  - Dynamic UI updates  
  - Reusable components  
  - Responsive user experience  

---

### Backend

- **Node.js & Express**
  - Handles server-side logic, routing, and API endpoints  

- **MongoDB (NoSQL Database)**
  - Provides flexible, schema-less data storage  
  - Ideal for evolving trip and user data models  
  - Integrates seamlessly with the MEAN stack  

---

## Functionality

### JSON vs. JavaScript
- JSON (JavaScript Object Notation) is used for data exchange between the frontend and backend  
- Enables seamless communication between:
  - Angular SPA  
  - RESTful API  

---

### Code Refactoring & Reusable Components
- Refactored code to improve:
  - Performance  
  - Maintainability  

- Developed modular Angular components for:
  - Trip cards  
  - Forms  
  - Lists  

**Benefits:**
- Reduced code duplication  
- Easier updates and scalability  
- Cleaner project structure  

---

## Testing

### API Testing
- Used Postman to test:
  - `GET`
  - `POST`
  - `PUT`
  - `DELETE` endpoints  

- Verified correct data storage and retrieval from MongoDB  

---

### Security Testing
- Implemented JWT (JSON Web Token) authentication

- Secured protected routes by:
  - Including tokens in request headers  
  - Using middleware for authorization  

**Key Concepts:**
- REST endpoints (e.g., `/api/trips`)  
- HTTP methods  
- Authorization headers  
- Middleware validation  

---

## Reflection

This project provided hands-on experience with full stack web development using the MEAN stack.

### Key Skills Developed
- Designing web application architecture  
- Building both MPA and SPA interfaces  
- Integrating a NoSQL database  
- Implementing authentication and security protocols 
- Writing modular, maintainable code  
- Testing APIs and debugging full stack interactions  

### Professional Impact
This experience strengthened my ability to develop scalable web applications and improved my readiness for roles requiring:
- Full stack development  
- Web application architecture  
- API design and integration  
