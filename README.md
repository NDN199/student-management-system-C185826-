# Student & Course Management System (C185826)

##  Project Overview
This is a full-stack web application designed for a Student and Course Management System. The project architecture follows a **Microservices-style** approach, integrating two distinct backend frameworks and two separate database systems into a unified Angular frontend.

---

##  System Architecture

The application is built using three primary, independent components:
1.  **Frontend:** Angular 17/18 (Implemented using Standalone Components)
2.  **Backend A:** ASP.NET Core 8.0 Web API (Managing Student Data)
3.  **Backend B:** Spring Boot 3.x REST API (Managing Course Data)



---

##  Technology Stack

### **Frontend (Angular)**
* **Framework:** Angular (Standalone Architecture)
* **Language:** TypeScript
* **Styling:** Bootstrap 5
* **Features:** Responsive UI, Reactive Forms, Multi-API Integration via HttpClient.

### **Backend Services**
* **Service 1 (.NET):** ASP.NET Core Web API 
    * **Database:** Microsoft SQL Server (MSSQL)
    * **ORM:** Entity Framework Core
* **Service 2 (Spring Boot):** Java Spring Boot REST API
    * **Database:** MySQL (via XAMPP/MariaDB)
    * **ORM:** Spring Data JPA

---

##  Project Structure

```text
├── backend/
│   ├── dotnet-api/       # ASP.NET Core Student Service
│   └── springboot-api/   # Spring Boot Course Service
├── frontend/
│   └── angular-app/      # Angular Frontend Application
├── database-scripts/     # SQL scripts for MSSQL and MySQL
└── README.md             # Project Documentation
