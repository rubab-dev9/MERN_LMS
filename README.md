# 📚 Learning Management System (LMS)

A **full-stack Learning Management System** built using the **MERN stack (MongoDB, Express.js, React, Node.js)**.  
It provides a structured platform for **students, mentors, and admins** to manage courses, assignments, communication, and announcements through role-based access control.

---

## 🚀 Live Overview

A scalable LMS platform designed to simulate real-world educational workflows with secure authentication and role-based dashboards.

---

## ✨ Key Features

### 🔐 Authentication & Security
- JWT-based secure authentication
- Role-based access control (Admin / Mentor / Student)
- Protected routes across frontend and backend

### 👨‍🏫 Role-Based Dashboards
- Separate dashboards for each user role
- Personalized data and permissions
- Admin control panel for system management

### 📚 Course Management
- Create, update, and delete courses
- Assign mentors to courses
- Enroll students into courses

### 📝 Assignments System
- Create assignments by mentors/admin
- Students can submit assignments
- Track submission status and feedback

### 📢 Announcements
- Broadcast important updates
- Role-based visibility of announcements

### 💬 Messaging System
- Basic communication between users
- Supports mentor-student interaction

---

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Context API
- Axios
- React Router

**Backend:**
- Node.js
- Express.js

**Database:**
- MongoDB (Mongoose)

**Authentication:**
- JSON Web Token (JWT)
- bcrypt for password hashing

---

## 🏗️ Project Architecture

Frontend (React)
     ↓
REST API (Express.js)
     ↓
Backend Logic (Node.js)
     ↓
Database (MongoDB)

---

## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/lms-project.git

### 2. Install dependencies 
#### Backend
```bash
cd backend
npm install

#### Frontend
```bash
cd frontend
npm install

### 3. Environment Variables
Create a .env file in backend:
```bash
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

### 4. Run the project
#### Backend
```bash
npm run dev

#### Frontend
```bash
npm start

## 🎯 Purpose of Project

This project demonstrates real-world full-stack development skills including:
- Role-based system design
- Secure authentication flow
- REST API development
- Scalable frontend architecture

## 👨‍💻 Author

Umme Rubab