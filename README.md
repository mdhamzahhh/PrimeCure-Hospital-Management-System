# PrimeCure – Full Stack Hospital Management System

![PrimeCure Banner](https://img.shields.io/badge/MERN-Full%20Stack-blue)
![Status](https://img.shields.io/badge/Status-Live-success)
![License](https://img.shields.io/badge/License-MIT-green)

PrimeCure is a modern full-stack Hospital Management System built with the MERN stack. The platform provides a complete healthcare management workflow including doctor management, medical services, appointment booking, authentication, image uploads, and admin management.

This project was professionally customized, restructured, debugged, and deployed with a production-ready architecture using:

* React + Vite
* Node.js + Express
* MongoDB Atlas
* Clerk Authentication
* Cloudinary
* Render
* Vercel

---

# Live Demo

## Frontend

[https://prime-cure-hospital-management-syst.vercel.app/](https://prime-cure-hospital-management-syst.vercel.app/)

## Admin Dashboard

[https://prime-cure-hospital-management-syst-lyart.vercel.app/](https://prime-cure-hospital-management-syst-lyart.vercel.app/)

## Backend API

[https://primecure-hospital-management-system.onrender.com](https://primecure-hospital-management-system.onrender.com)

---

# Features

## User Features

* Browse doctors
* Browse healthcare services
* Book appointments
* Authentication system
* Responsive UI
* Service details pages
* Doctor details pages
* Modern healthcare interface

## Admin Features

* Add doctors
* Add services
* Manage appointments
* Upload doctor/service images
* Dashboard management
* Authentication protected admin routes

## Backend Features

* REST API architecture
* MongoDB database integration
* JWT-based authorization
* Clerk authentication integration
* Cloudinary image uploads
* Secure environment variable configuration
* CORS protected APIs

---

# Tech Stack

## Frontend

* React
* Vite
* React Router DOM
* Tailwind CSS
* Axios
* Clerk React
* React Hot Toast
* Lucide React

## Backend

* Node.js
* Express.js
* MongoDB Atlas
* Mongoose
* JWT
* Multer
* Cloudinary
* Clerk Express
* CORS
* Dotenv

## Deployment

* Vercel (Frontend + Admin)
* Render (Backend)
* MongoDB Atlas (Database)

---

# Project Structure

```bash
PrimeCure-Hospital-Management-System/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── components/
│   └── pages/
│
├── admin/
│   ├── src/
│   ├── components/
│   └── pages/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── utils/
│
└── README.md
```

---

# Installation & Setup

## Clone Repository

```bash
git clone https://github.com/mdhamzahhh/PrimeCure-Hospital-Management-System.git
```

---

# Backend Setup

```bash
cd backend
npm install
npm run dev
```

## Backend Environment Variables

Create a `.env` file inside the backend folder:

```env
PORT=4000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

CLERK_SECRET_KEY=your_clerk_secret_key
CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

STRIPE_SECRET_KEY=your_stripe_secret_key
```

---

# Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

## Frontend Environment Variables

Create a `.env` file inside the frontend folder:

```env
VITE_API_URL=http://localhost:4000
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```

---

# Admin Setup

```bash
cd admin
npm install
npm run dev
```

## Admin Environment Variables

Create a `.env` file inside the admin folder:

```env
VITE_API_URL=http://localhost:4000
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```

---

# Deployment

## Frontend Deployment

* Hosted on Vercel
* SPA rewrite configuration enabled using `vercel.json`

## Backend Deployment

* Hosted on Render
* Production environment variables configured
* CORS configured for production domains

## Database

* MongoDB Atlas cloud database

---

# API Routes

## Doctors

```bash
/api/doctors
```

## Services

```bash
/api/services
```

## Appointments

```bash
/api/appointments
```

## Service Appointments

```bash
/api/services-appointments
```

---

# Authentication

Authentication is implemented using:

* Clerk Authentication
* JWT Authorization
* Protected Backend Routes
* Protected Admin Routes

---

# Production Features

* Environment variable architecture
* Dynamic API configuration
* Production CORS handling
* SPA routing support
* Cloud image uploads
* Secure API communication
* Responsive layout
* Modular folder structure

---

# Screenshots

> Add screenshots of:

* Homepage
* Doctors Page
* Services Page
* Admin Dashboard
* Appointment Page
* Login Page

---

# Future Improvements

* Payment integration
* Notification system
* Email confirmations
* Appointment status tracking
* Analytics dashboard
* Doctor availability calendar
* Patient profiles
* Search & filtering
* Pagination
* Dark mode
* Report generation

---

# Learning Outcomes

This project helped strengthen practical experience in:

* MERN stack architecture
* Full-stack deployment
* Production debugging
* Authentication systems
* REST API development
* MongoDB integration
* Cloudinary integration
* Environment variable management
* Vercel deployment
* Render deployment
* CORS debugging
* SPA routing configuration

---

# Author

## Md Hamzah

GitHub:
[https://github.com/mdhamzahhh](https://github.com/mdhamzahhh)

---

# License

This project is licensed under the MIT License.
