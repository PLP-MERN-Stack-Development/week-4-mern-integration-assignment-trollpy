
# 🧠 Code & Chaos – A MERN Stack Blog Platform

> A full-featured blog application built with the MERN stack, focused on clean architecture, role-based access, markdown publishing, and a beautiful responsive UI. Designed as a hands-on showcase of full-stack development expertise.

![MERN](https://img.shields.io/badge/MERN-Stack-61DAFB) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) ![Express](https://img.shields.io/badge/Express.js-404D59) ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB) ![Node.js](https://img.shields.io/badge/Node.js-43853D?logo=node.js&logoColor=white)

---

## 📖 Project Overview

**Code & Chaos** is a developer-focused blogging platform featuring secure authentication, rich text publishing with markdown, nested comments, and a responsive design. It was built as part of an integration challenge and showcases production-level architecture, performance optimizations, and scalable code structure.

---

## 🧩 Features Implemented

### 🔐 Authentication & Access
- User registration and login with JWT
- Role-based access control (Admin/User)
- Protected routes and session management

### 📝 Blogging & Comments
- Full CRUD for blog posts
- Markdown support for post body
- Secure image uploads (Multer)
- Nested comments with moderation features
- Categories and filtering

### 🎨 UI/UX
- Tailwind CSS 3 styling
- Light/dark theme toggle
- Mobile-responsive layout
- Smooth transitions and focus on readability

---

## ⚙️ Tech Stack

```
| Layer      | Technologies                          |
|------------|---------------------------------------|
| Frontend   | React, React Router, Tailwind CSS, Axios |
| Backend    | Node.js, Express.js, JWT, Bcrypt, Multer |
| Database   | MongoDB with Mongoose ODM             |
| Tooling    | Vite, ESLint, dotenv, Postman         |
```

---

## 🛠 Setup Instructions

### ✅ Prerequisites
- Node.js & npm installed
- MongoDB running locally or via cloud (e.g., MongoDB Atlas)

### 📦 Installation

```bash
# 1. Clone the repository
git clone https://github.com/trollpy/blog.git
cd blog

# 2. Install backend dependencies
npm install

# 3. Install frontend dependencies
cd client
npm install
```

### 🔐 Setup Environment Variables

In the root directory, create a `.env` file with:

```env
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

### 🚀 Running the App

```bash
# Start the backend
npm run dev

# Start the frontend
cd client
npm run dev
```

Frontend: http://localhost:3000  
Backend API: http://localhost:5000/api

---

## 🧪 API Documentation

### ✅ Auth API Endpoints

```
| Method | Endpoint        | Description              |
|--------|------------------|--------------------------|
| POST   | /auth/register   | Register a new user      |
| POST   | /auth/login      | Authenticate user & token|
| GET    | /auth/me         | Get logged-in user info  |
```

### 📝 Post API Endpoints

```
| Method | Endpoint       | Description                     |
|--------|----------------|---------------------------------|
| GET    | /posts          | Get all blog posts              |
| POST   | /posts          | Create a new post (auth only)   |
| GET    | /posts/:id      | Get a specific post by ID       |
| PUT    | /posts/:id      | Update post (auth + owner only)|
| DELETE | /posts/:id      | Delete post (auth + owner only)|
```

### 💬 Comment API Endpoints

```
| Method | Endpoint                | Description                 |
|--------|-------------------------|-----------------------------|
| POST   | /posts/:id/comments     | Add a comment to a post     |
| GET    | /posts/:id/comments     | Retrieve comments for a post|
| DELETE | /comments/:id           | Delete a comment (auth only)|
```

### 📂 Category API Endpoints

```
| Method | Endpoint       | Description                       |
|--------|----------------|-----------------------------------|
| GET    | /categories    | Get all available categories       |
| POST   | /categories    | Create a new category (admin only)|
```

---

## 📁 Project Structure

```
.
├── client/               # React + Vite frontend
│   ├── components/       # Reusable UI logic
│   ├── pages/            # Route views (Login, Register, etc.)
│   ├── hooks/            # Custom React hooks
│   ├── context/          # Auth context
│   ├── services/         # Axios API logic
│   └── utils/            # Constants & helpers
│
├── server/               # Node.js + Express backend
│   ├── controllers/      # Route logic
│   ├── models/           # Mongoose schemas
│   ├── routes/           # Express routes
│   ├── middleware/       # Auth, validation, error handler
│   ├── uploads/          # Uploaded image assets
│   └── utils/            # Custom helpers
│
└── seeder.js             # Optional data seeder
```

---

## 📸 Screenshots


- ![](./public/screenshot-home.png)
- ![](./public/screenshot-post.png)
- ![](./public/screenshot-editor.png)
- ![](./public/screenshot-dark.png)


---

## 🧠 What This Project Demonstrates

- ✅ REST API with Express + secure JWT authentication
- ✅ Scalable MongoDB schema design with Mongoose
- ✅ Role-based access control and protected routes
- ✅ React Hooks and Context API usage
- ✅ Tailwind CSS 3 proficiency
- ✅ Rich file structure and production-style modularity

---

## 🚫 Live Demo

⚠️ **Currently not deployed online.**  
To run locally, follow the setup instructions above.

---

## 📬 Contact

**Developer**: Thompho Sheriff  
**GitHub**: [@trollpy](https://github.com/trollpy)  
