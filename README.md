# Student & Course Management System (C185826)

## 📌 Project Overview
This is a full-stack web application developed for the Student Management System. The project demonstrates a **Microservices-style Architecture** by integrating two different backend frameworks and two separate database systems into a unified Angular frontend.

---

## 🏗️ System Architecture

The application is built using three primary components:
1.  **Frontend:** Angular (Standalone Components)
2.  **Backend A:** ASP.NET Core 8.0 Web API (Managing Students)
3.  **Backend B:** Spring Boot 3.x REST API (Managing Courses)

---

## 🛠️ Technology Stack

### **Frontend (Angular)**
* **Framework:** Angular 17/18 (Standalone)
* **Language:** TypeScript
* **UI Library:** Bootstrap 5
* **Features:** Single Page Application (SPA), REST API Integration.

### **Backend Services**
* **Service 1 (.NET):** ASP.NET Core Web API 
    * **Database:** Microsoft SQL Server (MSSQL)
    * **ORM:** Entity Framework Core
* **Service 2 (Java):** Spring Boot REST API
    * **Database:** MySQL
    * **ORM:** Spring Data JPA

---

## 🚀 Key Features

* **Student Management:** Full CRUD operations using .NET and MSSQL.
* **Course Management:** Full CRUD operations using Spring Boot and MySQL.
* **Modern UI:** Responsive dashboard developed using Angular standalone components.
* **API Documentation:** Interactive Swagger UI for both backend services.

---

## 📂 Project Structure

```text
├── backend/
│   ├── dotnet-api/       # ASP.NET Core Web API
│   ├── springboot-api/   # Spring Boot Web API
├── frontend/
│   └── angular-app/      # Angular Frontend Application
├── database-scripts/     # SQL scripts for MSSQL and MySQL
└── README.md             # Project Documentation
