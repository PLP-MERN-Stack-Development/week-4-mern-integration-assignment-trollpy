# Code & Chaos - Development Journal

> **MERN Stack Blog Application** | Full-stack development showcase with modern authentication, content management, and responsive design.

![MERN](https://img.shields.io/badge/MERN-Stack-61DAFB) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) ![Express](https://img.shields.io/badge/Express.js-404D59) ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB) ![Node.js](https://img.shields.io/badge/Node.js-43853D?logo=node.js&logoColor=white)

## 🎯 Key Features

**Authentication & Authorization**
- JWT-based secure login/registration system
- Protected routes and user session management
- Role-based access control (admin/user roles)

**Content Management**
- Full CRUD operations for blog posts
- Rich text editor with markdown support
- Featured article system and search functionality
- User dashboard for content management

**Modern UI/UX**
- Responsive design with dark theme
- Dynamic search and filtering
- Clean, professional interface optimized for readability

## 🛠 Tech Stack

**Frontend:** React.js • React Router • Axios • TAILWINDCSS3  
**Backend:** Node.js • Express.js • JWT Authentication  
**Database:** MongoDB • Mongoose ODM  
**Deployment:** [Your deployment platform]

## 🚀 Quick Start

```bash
# Clone and install
git clone https://github.com/trollpy/blog.git
cd blog
npm install && cd client && npm install

# Set environment variables
echo "MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret" > .env

# Run development
npm run dev        # Backend (port 5000)
cd client && npm start  # Frontend (port 3000)
```

## 🔧 Technical Highlights

- **RESTful API Design** with Express.js middleware and error handling
- **MongoDB Schema Design** with Mongoose for data modeling
- **JWT Authentication** with protected routes and token validation  
- **React Hooks & Context API** for state management
- **Responsive CSS** with modern layout techniques
- **Input Validation** and sanitization for security

## 📊 Project Structure
```
blog/
├── client/          # React frontend
├── models/          # MongoDB schemas  
├── routes/          # Express API routes
├── middleware/      # Auth & validation
└── controllers/     # Business logic
```

---
**Live Demo:** [Add your deployment URL]  
**Contact:** [Your professional email]