# 🚌 GoBus Backend
![.NET](https://img.shields.io/badge/.NET-7.0-blue)

## 📝 Overview
**GoBus** is a full-featured backend system for managing bus reservations, built with **ASP.NET Core 7.0**.  
It provides a powerful and secure RESTful API for handling bookings, payments, and user management.

---

## 🚀 Key Features
- 🔐 Secure JWT Authentication and Authorization
- 💳 Online payment integration with Stripe
- 📆 Full booking management (create, update, cancel)
- 📈 Admin dashboard and analytics (if applicable)
- ⚙️ Hangfire support for scheduled background jobs
- 🔄 Synchronous and asynchronous request handling
- 🧠 In-memory caching for performance optimization
- 🌐 Interactive API documentation with Swagger

---

## 🛠️ Tech Stack
- ASP.NET Core 7.0
- Entity Framework Core
- SQL Server
- Stripe.NET
- Hangfire
- Azure Services (Optional)
- JWT Authentication
- Swagger / OpenAPI

---

## 🏗️ Project Structure
```plaintext
GoBye/
├── GoBye.API/       → API layer (Endpoints & Controllers)
├── GoBye.BLL/       → Business logic layer (Services & Managers)
└── GoBye.DAL/       → Data access layer (Repositories & EF Context)
