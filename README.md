# 🌤️ HeavenHub
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
![Node.js](https://img.shields.io/badge/Node.js-18+-green)
![Express.js](https://img.shields.io/badge/Express.js-Framework-lightgrey)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-green)
![Contributions welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen)
![Status](https://img.shields.io/badge/Status-Active-success)

---

**HeavenHub** — A modern web platform that connects travelers with unique stays around the world.  
Users can explore destinations, list properties, and manage bookings with a clean, intuitive interface.

---

## 📑 Table of Contents
1. [Overview](#overview)  
2. [Features](#features)  
3. [Tech Stack](#tech-stack)  
4. [Folder Structure](#folder-structure)  
5. [Installation & Setup](#installation--setup)  
6. [Usage](#usage)  
7. [Environment Variables](#environment-variables)  
8. [Screenshots](#screenshots)  
9. [Contributing](#contributing)  
10. [License](#license)  
11. [Contact](#contact)

---

## 🏖️ Overview
**HeavenHub** is a **Node.js + Express** based web application designed to simplify travel and property management.  
Property owners can list their accommodations, and travelers can explore, request, and book stays seamlessly.  
It includes authentication, booking workflows, and user-friendly **EJS-based** views.

---

## 🚀 Features
- 🏡 **Property Management** – Add, view, and update property listings.  
- 📅 **Booking System** – Travelers can request and confirm bookings.  
- 🔐 **Authentication** – Secure login, signup, and session handling.  
- 🧩 **Modular Architecture** – Organized into models, routes, and controllers.  
- 🎨 **Templating** – Beautiful, server-rendered pages with EJS.  
- ☁️ **Cloud Config** – Easy configuration for deployment.  
- ⚙️ **Admin Tools** – Manage users, listings, and bookings efficiently.

---

## 🧰 Tech Stack
| Category | Technology |
|-----------|-------------|
| **Backend** | Node.js, Express.js |
| **Templating Engine** | EJS |
| **Database** | MongoDB / Mongoose |
| **Utilities** | Middleware, Custom Helpers |
| **Deployment** | Cloud / Localhost ready |
| **Version Control** | Git & GitHub |

---

## 🗂️ Folder Structure

HeavenHub/
├── controllers/ # Application logic and route handlers
├── init/ # Initialization / seeding scripts
├── models/ # Database models and schemas
├── public/ # Static files (CSS, images, JS)
├── routes/ # Express routes
├── utils/ # Helper functions
├── views/ # EJS templates for UI
├── app.js # Main entry point
├── cloudconfig.js # Cloud configuration file
├── middleware.js # Custom middlewares
├── schema.js # Database structure
├── package.json
└── .gitignore



---

## ⚙️ Installation & Setup
### Prerequisites
- Node.js & npm installed  
- MongoDB (local or cloud) configured  

### Steps
```bash
# 1️⃣ Clone the repository
git clone https://github.com/Rakeshivam/HeavenHub.git
cd HeavenHub

# 2️⃣ Install dependencies
npm install

# 3️⃣ Create a .env file

touch .env
PORT=3000
DB_URI=your_database_connection_string
JWT_SECRET=your_jwt_secret

Now open 👉 http://localhost:3000 in your browser.


💻 Usage

Register or log in as a user.

Explore properties or add your own listings.

Request bookings and manage approvals.

Admins can review and manage all bookings.

