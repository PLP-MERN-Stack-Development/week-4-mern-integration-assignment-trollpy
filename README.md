 Code & Chaos – Full-Stack Blog Platform

    A feature-rich MERN stack blog application designed with production-level architecture, modern authentication, dynamic content handling, and a seamless user experience.
    Built as part of a full-stack integration challenge to demonstrate practical expertise across frontend, backend, and API design.

MERN MongoDB Express React Node.js
💡 Project Overview

Code & Chaos is a full-stack blogging platform built to support authenticated content creation, commenting, and rich user experiences. The application reflects a modular, scalable MERN architecture, covering:

    Robust authentication and role-based access

    Complete blog post CRUD with markdown support

    Real-time comment management system

    Secure image uploads and input validation

    Responsive UI with dark/light mode

🧩 Key Features
🔐 Authentication & Authorization

    JWT-based login & registration

    Role-based access control (admin/user)

    Secure password hashing and token storage

📝 Content & Comments

    Rich blog post editor with image and markdown support

    Full CRUD for posts, categories, and comments

    Nested comment system

    Dynamic search and filtering

🖥️ UI & UX

    Mobile-friendly, responsive layout with TailwindCSS

    Toggleable dark/light theme

    User dashboard for content management

    Clean, minimal interface optimized for readability

🛠 Tech Stack
Layer	Technologies
Frontend	React, React Router, Tailwind CSS, Axios
Backend	Node.js, Express.js, JWT, Bcrypt, Multer
Database	MongoDB with Mongoose ODM
Tooling	Vite, ESLint, dotenv, Postman
Security	Input sanitization, file validation, auth middleware
🗂️ Project Structure

.
├── client/               # Frontend (React + Vite)
│   ├── components/       # Reusable UI & logic split by domain
│   ├── pages/            # Route-specific views
│   ├── context/          # Global auth context
│   ├── hooks/            # Custom reusable hooks
│   ├── services/         # Axios API logic
│   └── utils/            # Constants & helpers
│
├── server/               # Backend (Express API)
│   ├── controllers/      # Business logic
│   ├── models/           # Mongoose schemas
│   ├── routes/           # API endpoints
│   ├── middleware/       # Auth, validation, error handling
│   ├── utils/            # Custom error and response helpers
│   └── config/           # DB config
│
├── uploads/              # Uploaded image storage
├── seeder.js             # Data seeding script
└── server.js             # API entry point

🚀 Getting Started

    You'll need Node.js, MongoDB, and npm installed.

1. Clone the repository

git clone https://github.com/PLP-MERN-Stack-Development/week-4-mern-integration-assignment-trollpy.git
cd blog

2. Install dependencies

# Backend
npm install

# Frontend
cd client
npm install

3. Environment setup

Create a .env file in the root directory:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

4. Run the application

# Start backend
npm run dev

# In another terminal: start frontend
cd client
npm run dev

The app will be available at:

    Frontend: http://localhost:5173

    Backend: http://localhost:5000/api

🧠 What This Project Demonstrates

    ✅ Real-world REST API design with Express and route protection

    ✅ Modular, maintainable frontend with React Context + custom hooks

    ✅ File uploads and validation using Multer

    ✅ Scalable MongoDB schema design

    ✅ Tailwind CSS mastery for fast, responsive UI

    ✅ Full understanding of the MERN stack from database to UI

📌 Status

This project was built as part of a learning + demonstration exercise and is fully functional locally, but not yet deployed.
📫 Contact

Developer: Thompho Sheriff
GitHub: https://github.com/trollpy