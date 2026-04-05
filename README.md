# 💰 Finance Dashboard Backend

## 🚀 Overview
This project is a backend system for managing financial data with role-based access control.  
It allows users to track income, expenses, and view analytical insights through secure APIs.

---

## 🏗️ Architecture
The project follows a layered architecture:

- **Controller Layer** → Handles API requests
- **Service Layer** → Contains business logic
- **Repository Layer** → Handles database operations
- **Security Layer** → JWT-based authentication & authorization

---

## 🗄️ Database Design

### Entities:
- **User**
- **Role**
- **FinancialRecord**

### Relationships:
- One User → Many Financial Records
- One Role → Many Users

---

## 🛠️ Tech Stack

- Java
- Spring Boot
- Spring Security (JWT)
- Hibernate / JPA
- MySQL / PostgreSQL (or H2)
- Swagger (API Documentation)

---

## 👥 Roles & Access Control

| Role    | Permissions |
|--------|------------|
| Viewer | View dashboard only |
| Analyst | View records and analytics |
| Admin | Full access (CRUD + user management) |

---

## 📌 Features

- 🔐 JWT Authentication & Authorization  
- 👥 Role-based access control  
- 📊 Dashboard analytics (income, expenses, trends)  
- 💾 Financial records CRUD operations  
- 🔎 Filtering (date, category, type)  
- ⚠️ Global exception handling  
- 📄 API documentation (Swagger)  

---

## 🔗 API Modules

- Auth APIs (Login/Register)
- User APIs
- Financial Records APIs
- Dashboard APIs

---

## ⚙️ How to Run

```bash
git clone https://github.com/Adityaraj2066/finance-dashboard-backend.git
cd finance-dashboard-backend
