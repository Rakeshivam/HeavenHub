# 🌤️ HeavenHub

<div align="center">

### ✨ A Modern Travel & Stay Booking Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
![Node.js](https://img.shields.io/badge/Node.js-18+-green)
![Express.js](https://img.shields.io/badge/Express.js-Framework-lightgrey)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-green)
![EJS](https://img.shields.io/badge/Templating-EJS-orange)
![Status](https://img.shields.io/badge/Status-Active-success)
![Contributions welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen)

</div>

---

## 📖 Overview

**HeavenHub** is a full-stack web platform that connects **travelers with unique stays around the world**.

Users can:
- Explore destinations
- List their own properties
- Manage bookings
- Handle authentication securely

Built using **Node.js + Express + MongoDB + EJS**, HeavenHub focuses on **performance, scalability, and clean architecture**.

It demonstrates real-world backend development practices including:
- MVC structure
- RESTful routing
- Authentication
- Database modeling
- Middleware handling

---

## 📑 Table of Contents

1. Overview  
2. Features  
3. Tech Stack  
4. Architecture  
5. Folder Structure  
6. Installation & Setup  
7. Environment Variables  
8. Usage  
9. API Flow  
10. Screenshots  
11. Contributing  
12. License  
13. Contact  

---

## 🚀 Features

### 🏡 Property Management
- Add listings
- Edit details
- Upload images
- Delete properties

### 📅 Booking System
- Travelers can request bookings
- Owners can approve/reject
- Booking history tracking

### 🔐 Authentication & Security
- Signup / Login
- Sessions / JWT
- Protected routes
- Secure password handling

### 🧩 Clean Architecture
- MVC pattern
- Modular routes
- Reusable middleware
- Organized folder structure

### 🎨 UI/UX
- EJS templating
- Responsive design
- Server-side rendering
- Clean user interface

---

## 🧰 Tech Stack

| Category | Technology |
|-----------|-------------|
| **Backend** | Node.js, Express.js |
| **Frontend** | HTML, CSS, JavaScript |
| **Templating** | EJS |
| **Database** | MongoDB + Mongoose |
| **Authentication** | Sessions / JWT |
| **Architecture** | MVC Pattern |
| **Version Control** | Git & GitHub |

---

## 🧠 Architecture

```
Client (Browser)
       ↓
Express Routes
       ↓
Controllers
       ↓
Models (MongoDB)
       ↓
Database
```

### Flow:
1. User sends request  
2. Route handles it  
3. Controller processes logic  
4. Model interacts with DB  
5. Response rendered via EJS  

---

## 🗂️ Folder Structure

```
HeavenHub/
│
├── controllers/        # Application logic
├── init/               # Initialization / seed scripts
├── models/             # Database schemas
├── public/             # Static files (CSS, images, JS)
├── routes/             # Express routes
├── utils/              # Helper utilities
├── views/              # EJS templates
│
├── app.js              # Main entry point
├── middleware.js       # Custom middleware
├── schema.js           # Validation schemas
├── cloudconfig.js      # Cloud config
├── package.json
└── .gitignore
```

---

## ⚙️ Installation & Setup

### 🔹 Prerequisites
- Node.js (v18+ recommended)
- npm
- MongoDB (Local or Atlas)

---

### 🔹 Steps

### 1️⃣ Clone Repository
```
git clone https://github.com/Rakeshivam/HeavenHub.git
cd HeavenHub
```

### 2️⃣ Install Dependencies
```
npm install
```

### 3️⃣ Create .env File
Create a `.env` file in root directory:

```
PORT=3000
DB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
SESSION_SECRET=your_session_secret
```

### 4️⃣ Start Server
```
npm start
```

### 5️⃣ Open Browser
```
http://localhost:8080
```

---

## 💻 Usage

### For Travelers
- Register/Login
- Browse listings
- Request bookings
- Manage reservations

### For Property Owners
- Add new properties
- Update listings
- Accept/Reject bookings

### For Admins
- Manage users
- Manage listings
- Monitor platform activity

---

## 🔌 API Flow (Example)

```
GET    /listings        → View all properties
GET    /listings/:id    → View single property
POST   /listings        → Add new property
POST   /bookings        → Create booking
POST   /login           → Authenticate user
```

---

## 📸 Screenshots

> Add your project screenshots here  
Example:

```
/public/images/homepage.png
/public/images/dashboard.png
```

---

## 🔧 Future Improvements

- Payment gateway integration
- Image uploads (Cloudinary)
- Reviews & ratings
- Admin dashboard
- Notifications
- REST API version
- Docker support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo  
2. Create a new branch  
3. Make changes  
4. Commit  
5. Open Pull Request  

---

## ⭐ Support

If you like this project, please give it a **star ⭐**  
It helps and motivates future improvements.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Contact

**Rakesh**

GitHub → https://github.com/Rakeshivam  
Portfolio → https://rakeshivam.github.io  

---

<div align="center">

### 🌤️ HeavenHub – Travel Made Simple  
### ❤️ Thanks for visiting!

</div>
