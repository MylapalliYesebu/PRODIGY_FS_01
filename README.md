# PRODIGY_FS_01
A secure authentication system using Spring Boot (Backend) and React.js (Frontend).
# Secure User Authentication System

## 📌 Project Overview

This project implements a secure authentication system that allows users to **sign up**, **log in securely**, and **access protected routes** only after successful authentication. It follows standard security practices, including password hashing, session management, and role-based access control.

## 🛠 Tech Stack

- **Backend**: Spring Boot (Java), Spring Security, JWT, MySQL
- **Frontend**: React.js, Axios
- **Authentication**: JSON Web Tokens (JWT), BCrypt password hashing

## 🚀 Features

✅ User Registration (Signup) with encrypted passwords\
✅ Secure Login with token-based authentication\
✅ Protected routes (only authenticated users can access)\
✅ Role-based access control (admin/user) *(Optional)*\
✅ Session management with JWT\
✅ Logout functionality

## 📂 Folder Structure

```
secure-user-authentication/
│── backend/         # Spring Boot backend
│── frontend/        # React.js frontend
│── README.md        # Project documentation
```

## 📖 Setup Instructions

### 🔹 Backend Setup (Spring Boot)

1️⃣ Navigate to the `backend/` folder:

```bash
cd backend
```

2️⃣ Install dependencies:

```bash
mvn clean install
```

3️⃣ Run the Spring Boot application:

```bash
mvn spring-boot:run
```

### 🔹 Frontend Setup (React.js)

1️⃣ Navigate to the `frontend/` folder:

```bash
cd frontend
```

2️⃣ Install dependencies:

```bash
npm install
```

3️⃣ Start the React development server:

```bash
npm start
```

## 📌 API Endpoints

### **🔐 Authentication Routes**

| Method | Endpoint             | Description            |
| ------ | -------------------- | ---------------------- |
| POST   | `/api/auth/register` | User Signup            |
| POST   | `/api/auth/login`    | User Login (JWT Token) |
| GET    | `/api/auth/user`     | Get User Details       |

## 💡 Next Steps

- Implement **Forgot Password** functionality
- Add **OAuth (Google, GitHub Login)** *(Optional)*

---

🔹 **Author:** Mylapalli Yesebu\
🔹 **GitHub:** [MylapalliYesebu](https://github.com/MylapalliYesebu)

