# LLEGAR – Rental Listing Backend API

A RESTful backend service for a rental listing platform.  
Built with **Node.js**, **Express.js**, and **MongoDB**.

---

## 🛠️ Tech Stack
- Node.js & Express.js
- MongoDB (Mongoose)
- JWT Authentication
- RESTful API Design

---

## 🚀 Features
- User registration/login (JWT)
- CRUD for rental listings
- Middleware for validation and authentication

---

## 📡 API Endpoints
- You can explore and test the full API using the Postman documentation below:

👉 View LLEGAR API Docs on Postman: [https://documenter.getpostman.com/view/24721331/2s93zFYL45]

- Example routes include:

- POST /api/auth/register – Register new user
- POST /api/auth/login – Authenticate user
- GET /api/listings – Fetch all listings
- POST /api/listings – Create new listing (auth required)
- PUT /api/listings/:id – Update listing (auth required)
- DELETE /api/listings/:id – Delete listing (auth required)

---

## ⚙️ Setup
```bash
git clone https://github.com/Mohamedkazlak/LLEGAR.git
cd LLEGAR
npm install
# Add .env file with MONGO_URI and JWT_SECRET
npm start

