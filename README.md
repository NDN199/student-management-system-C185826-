# Student & Course Management System (C185826)

##  Project Overview
This project is a sophisticated Full-Stack Web Application developed as part of the "Development of Web Applications & Projects" unit. The system is designed to handle Student and Course registrations using a **decoupled Microservices-style architecture**.

Unlike traditional monolithic applications, this system separates the concerns of student management and course management into two distinct backend services, integrated seamlessly into a modern Angular frontend.

---

##  System Architecture & Logic

The system is built on three main pillars to ensure high availability and scalability:

1.  **Student Management Service (.NET):** A robust REST API built with ASP.NET Core 8.0. It manages all student-related data and persists it in a Microsoft SQL Server (MSSQL) database using Entity Framework Core.
2.  **Course Management Service (Spring Boot):** A high-performance Java-based service that handles course catalogs and details, persisting data in a MySQL database via Spring Data JPA.
3.  **Unified Frontend (Angular):** A single-page application (SPA) that acts as the orchestration layer, fetching data from both backends simultaneously to provide a unified user experience.



---

##  Detailed Technology Stack

### **Frontend**
* **Framework:** Angular 17/18 (Standalone Component Architecture)
* **Design:** Bootstrap 5 for a clean, responsive User Interface.
* **Communication:** Angular `HttpClient` used for asynchronous REST API consumption.
* **Routing:** Implemented for seamless navigation between Student and Course modules.

### **Backend Services**
* **Primary Service (C#):** ASP.NET Core Web API 8.0.
    * **Database:** Microsoft SQL Server.
    * **Features:** Dependency Injection, Repository Pattern, and Swagger/OpenAPI documentation.
* **Secondary Service (Java):** Spring Boot 3.x.
    * **Database:** MySQL (XAMPP/MariaDB).
    * **Features:** Hibernate/JPA for data persistence and Maven for dependency management.

---

##  Key Features Implemented

* **Dual-Backend Integration:** Demonstrates the ability to communicate with two different server environments from one frontend.
* **CRUD Operations:** Complete Create, Read, Update, and Delete functionalities for both Students and Courses.
* **Database Diversity:** Expertise in managing both Relational Database Management Systems (RDBMS) - MSSQL and MySQL.
* **Modern Angular Logic:** Utilizes the latest Standalone components for better performance and reduced bundle size.
* **API Documentation:** Fully documented endpoints via Swagger UI for easy testing.

---

##  Project Structure

```text
├── backend/
│   ├── dotnet-api/       # Source code for Student Service (C#)
│   └── springboot-api/   # Source code for Course Service (Java)
├── frontend/
│   └── angular-app/      # Angular source code (Standalone components)
├── database-scripts/
│   ├── student_db.sql    # MSSQL Database script
│   └── course_db.sql     # MySQL Database script
└── README.md             # Project documentation
