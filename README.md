# 🛒 MERN E-Commerce Website

A full-featured e-commerce application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). 
This project was developed during my internship at **Zidio Technologies (Apr–Jun 2025)**. 
It features a comic superhero and starry night themed design with 
full shopping functionality, user management, Stripe-based payments, and an admin dashboard.

---

## 🌟 Features

### 👥 User Features
- Browse products with themed UI
- Add items to cart
- Update item quantity or remove from cart
- Responsive design for desktop and mobile
- Secure checkout flow with **Stripe Payment Gateway**

### 💳 Stripe Payment Integration
- Integrated **Stripe Checkout** for secure payments
- Stripe test environment support
- Simulates a real e-commerce checkout process
- Auto-redirection on successful payment

### 🔐 Auth
- User registration and login
- JWT-based authentication
- Protected routes for logged-in users and admins

### 🛠 Admin Features
- Admin login
- Create and delete products
- Dashboard overview

---

## 🧱 Tech Stack

### 🌐 Frontend
- **React.js** – UI framework
- **React Router DOM** – Routing
- **Tailwind CSS** – Utility-first styling
- **Redux Toolkit** – State management for cart/auth
- **Axios** – HTTP requests
- **Framer Motion** – Animations
- **Stripe.js + React Stripe** – Secure payment processing

### 🖥 Backend
- **Node.js + Express.js** – Server-side APIs
- **MongoDB + Mongoose** – NoSQL database
- **jsonwebtoken** – JWT auth
- **bcrypt.js** – Password hashing
- **Stripe SDK** – Payment intent creation and session handling

### 🔧 Tools & Utilities
- **Postman** – API testing
- **Cloudinary** – Product image upload (optional)
- **Vite / Webpack** – Frontend bundler
- **Render / Railway** – Suggested deployment platform
- **GitHub** – Version control

---

## 🧾 Stripe Test Cards

Use this card number for testing payments:

```bash
Card Number: 4242 4242 4242 4242
Expiry Date: Any future date
CVC: Any 3-digit code
ZIP: Any valid ZIP
