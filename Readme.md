# 🚀 Backend Practice Project (Node.js + Express + MongoDB)

This project is a hands-on backend development practice repository where I am rebuilding and strengthening my core backend skills using **Node.js, Express.js, and MongoDB (Mongoose)**.

The goal of this project is not just to build an API, but to deeply understand how a real-world backend server works, including authentication, database modeling, and API architecture.

---

## 📌 Objectives

* Strengthen Node.js fundamentals
* Understand Express.js routing and middleware
* Learn proper project structure
* Practice MongoDB database design
* Master Mongoose schema & model relationships
* Implement Authentication & Authorization
* Build production-like REST APIs

---

## 🛠️ Tech Stack

* **Runtime:** Node.js
* **Framework:** Express.js
* **Database:** MongoDB
* **ODM:** Mongoose
* **Authentication:** JWT (JSON Web Token)
* **Environment Variables:** dotenv
* **API Testing:** Postman / Thunder Client
* **Password Hashing:** bcrypt

---

## 📁 Project Structure

```
project-root/
│── src/
│   ├── config/        # Database connection
│   ├── controllers/   # Business logic
│   ├── models/        # Mongoose schemas
│   ├── routes/        # API routes
│   ├── middlewares/   # Custom middlewares (auth, error handling)
│   ├── utils/         # Helper functions
│   └── app.js         # Express app setup
│
│── .env
│── server.js
│── package.json
```

---

## ✨ Features

* User Registration
* User Login (JWT Authentication)
* Protected Routes
* CRUD Operations
* Password Hashing (bcrypt)
* Error Handling Middleware
* MongoDB Database Integration
* Clean MVC Architecture

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/kawsar121/Express-With-Mongoose.git
```

### 2️⃣ Go to project directory

```
cd your-repo-name
```

### 3️⃣ Install dependencies

```
npm install
```

### 4️⃣ Create .env file

Create a `.env` file in the root folder and add:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_super_secret_key
```

### 5️⃣ Run the server

```
npm run dev
```

Server will run on:

```
http://localhost:5000
```

---

## 🔐 API Endpoints (Example)

| Method | Route              | Description               |
| ------ | ------------------ | ------------------------- |
| POST   | /api/auth/register | Register user             |
| POST   | /api/auth/login    | Login user                |
| GET    | /api/users         | Get all users (Protected) |
| GET    | /api/users/:id     | Get single user           |
| PUT    | /api/users/:id     | Update user               |
| DELETE | /api/users/:id     | Delete user               |

---

## 🧠 What I Am Learning

* How backend communicates with database
* Middleware execution flow
* Token based authentication
* MVC architecture
* Error handling in Express
* Secure password storage
* REST API best practices

---

## 📌 Future Improvements

* Role Based Authorization (Admin/User)
* Refresh Token System
* Email Verification
* File Upload (Multer + Cloudinary)
* Rate Limiting & Security (Helmet, CORS)
* API Documentation (Swagger)

---

## 👨‍💻 Author

**Tohidul Islam Kawsar Bhuiyan**
Aspiring MERN Stack Developer

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
