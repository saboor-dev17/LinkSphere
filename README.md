# 🌐 LinkSphere

<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Frontend-React-61DAFB?style=for-the-badge&logo=react" />
  <img src="https://img.shields.io/badge/Backend-Node.js-339933?style=for-the-badge&logo=node.js" />
  <img src="https://img.shields.io/badge/Database-MongoDB-47A248?style=for-the-badge&logo=mongodb" />
</p>

## 📖 Overview

**LinkSphere** is a full-stack professional networking platform inspired by LinkedIn. It was developed as a university semester project to demonstrate modern web development practices, including authentication, RESTful APIs, database integration, and responsive user interface design.

The platform enables users to build professional profiles, connect with others, and interact through posts and comments in a social networking environment.

---

## ✨ Features

- 🔐 Secure user authentication using JWT
- 👤 User registration and profile management
- 📝 Create, edit, and delete posts
- ❤️ Like and comment on posts
- 🤝 Send and manage connection requests
- 📰 Personalized activity feed
- 📱 Responsive user interface
- ⚡ RESTful backend API built with Express.js

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Authentication
- JSON Web Token (JWT)

### Deployment
- Render

---

## 📂 Project Structure

```
LinkSphere/
├── client/          # React frontend
├── server/          # Express backend
├── models/          # MongoDB models
├── routes/          # API routes
├── controllers/     # Business logic
├── middleware/      # Authentication & utilities
└── README.md
```

> *Note: Folder names may vary slightly depending on the repository structure.*

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/saboor-dev17/LinkSphere.git
cd LinkSphere
```

### Install dependencies

Backend:

```bash
cd server
npm install
```

Frontend:

```bash
cd client
npm install
```

### Configure environment variables

Create a `.env` file for the backend with the required values:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### Run the application

Backend:

```bash
npm start
```

Frontend:

```bash
npm start
```

---

## 🔐 Authentication

The application uses **JWT (JSON Web Tokens)** for secure authentication and authorization.

- User registration and login
- Protected API routes
- Secure token validation
- Session-based access to user resources

---

## 📚 Key Learning Outcomes

- MERN stack application development
- RESTful API design
- JWT authentication and authorization
- MongoDB database integration
- Responsive frontend development with React
- CRUD operations
- Client-server architecture
- Project collaboration using Git and GitHub

---

## 👥 Academic Project

This project was developed as part of a university software engineering course to explore full-stack web application development and collaborative software development practices.

---

## 📄 License

This project is intended for educational purposes.

## 📄 Author
Abdul Saboor