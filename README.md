# 💰 Personal Finance Manager (React + Spring Boot + MySQL + JWT)

A **Full Stack Money Management Web Application** to track Income, Expenses, Categories, and Analytics with secure JWT Authentication.

Built using **React + Spring Boot + MySQL** with Email Notifications, Excel Export, Cloudinary Upload, and Dashboard Analytics.

---

## 🚀 Live Demo

Frontend: https://your-netlify-link.netlify.app  
Backend API: https://your-render-backend-link.onrender.com  

---

## 📌 Project Introduction

This project helps users manage their personal finances efficiently by:

- Tracking income & expenses
- Categorizing transactions
- Viewing analytics dashboard
- Exporting transactions to Excel
- Receiving email reminders
- Secure login using JWT authentication

---

## 🧰 Tech Stack

### Frontend
- React.js
- Axios
- Tailwind CSS
- Lucide Icons
- React Hot Toast
- Emoji Picker
- React Charts
- Reusable Modal
- Loader Spinner

### Backend
- Spring Boot
- Spring Data JPA
- Spring Security + JWT
- MySQL Database
- Email Service (SMTP)
- Excel Export (Apache POI)
- Cloudinary Image Upload

---

## 🔐 Authentication & Security

- JWT Based Authentication
- Role-Based Authorization
- Secure Password Hashing
- Protected APIs

---

## 🔧 Features

### 👤 User
- Register with Email Verification
- Login with JWT Authentication
- Upload Profile Picture (Cloudinary)
- Daily Email Reminders

### 💰 Finance Management
- Add Income & Expense
- Category Management
- Validation & Form Handling
- Emoji Category Icons
- Filter Transactions
- Dashboard Analytics (Charts)

### 📊 Data & Reports
- Download Transactions in Excel
- Email Transaction Reports
- Dashboard Summary
- Monthly & Category-wise Analysis

---

## 📦 Backend APIs

- Register API (Email Config)
- Login API (JWT Auth)
- Category API
- Income API
- Expense API
- Dashboard API
- Filter API
- Notifications API
- Excel Download API
- Email Send API

---

## 💻 Frontend Modules

- Signup & Login Module
- Profile Upload
- Sidebar & Menubar
- Category Module
- Income Module
- Expense Module
- Filter Module
- Dashboard Module
- Excel Download & Email Module

---

## 📁 Project Structure
finance-app/
│
├── backend (Spring Boot)
│ ├── controller
│ ├── service
│ ├── repository
│ ├── security (JWT)
│ └── config
│
├── frontend (React)
│ ├── components
│ ├── pages
│ ├── services (Axios)
│ ├── utils
│ └── assets


---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/react-springboot-finance-app.git

2️⃣ Backend Setup (Spring Boot)
cd backend

Configure application.properties

spring.datasource.url=jdbc:mysql://localhost:3306/finance_db
spring.datasource.username=root
spring.datasource.password=yourpassword

jwt.secret=your-secret-key

spring.mail.username=your-email@gmail.com
spring.mail.password=your-app-password

Run backend:

mvn spring-boot:run

3️⃣ Frontend Setup (React)
cd frontend
npm install
npm start

🌍 Deployment

Backend → Render

Frontend → Netlify

Database → MySQL (Railway / Local)

Images → Cloudinary

📊 Future Improvements

Budget Limit Alerts

Mobile Responsive UI

Dark Mode

Multi-user roles (Admin/User)

Recurring Transactions

PWA Support

👨‍💻 Author

Tapan Manna
