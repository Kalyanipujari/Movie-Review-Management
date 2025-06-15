# 🎬 Movie Review Management System

A full-stack web application developed as part of the **CDAC Web-based Java Programming (WJP) module**, designed to manage and explore movie reviews with role-based access control.

## 🚀 Features

### 🔐 Authentication & Authorization
- JWT-based authentication system
- Role-based access (Admin & User)
- Admin registration protected by a secret key

### 👤 User Functionality
- Register and login
- Browse and explore movies
- View reviews
- Add reviews (only after login)

### 🛠️ Admin Functionality
- Add, edit, and delete movie records
- View all reviews
- Delete inappropriate reviews

### 🧾 Form Validation
- Client-side and server-side validation for:
  - Registration and Login
  - Movie and Review forms
  - Feedback form

---

## 🧱 Tech Stack

| Layer        | Technology         |
|--------------|--------------------|
| Frontend     | React.js           |
| Backend      | Spring Boot (Java) |
| Database     | MySQL              |
| Security     | JWT Authentication |
| API Protocol | REST               |

---

## 🛠️ Setup Instructions

### ✅ Prerequisites
- Java 17+
- Spring Boot
- MySQL Server
- Maven

### ⚙️ Backend Setup
```bash
cd backend
# Configure MySQL credentials in application.properties
mvn spring-boot:run
```
### ⚙️ Frontend Setup
```
cd frontend
npm install
npm run dev
```
---
👨‍💻 Contributors
- Kalyani Pujari
- Mukta Wagh
- Shankar Parab
---

📜 License
This project is for educational purposes as part of CDAC. You are free to fork, learn, and modify as needed.

---

Let me know if you'd like:
- To include API endpoints documentation.
- Swagger UI instructions.
- Docker support section (if applicable).
- A separate `.env.example` file setup.

I can generate those too.

