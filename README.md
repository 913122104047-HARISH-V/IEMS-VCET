# 🏫 IEMS-VCET — Internal Event Management System

A full-stack web application for managing college events, registrations, and announcements at VCET (Velammal College of Engineering and Technology).

> 👥 **Team Project** — Developed collaboratively with a team of 4. This is my fork of the shared repository.  
> 🔗 Original repository: [Alex-Pandian/IEMS-VCET](https://github.com/Alex-Pandian/IEMS-VCET)  
> 🌐 Live Demo: [iemsfrontend.vercel.app](https://iemsfrontend.vercel.app)

---

## 🚀 Features

- 🔐 Role-based access control (Student / Faculty / Admin)
- 📅 Event creation, editing, and deletion by admins
- 📝 Student event registration with confirmation
- 📢 Announcements and notifications board
- 👤 User profile management
- 📊 Admin dashboard with event and registration stats

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | React, JavaScript, CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB Atlas, Mongoose |
| Auth | JWT (JSON Web Tokens) |

---

## 📁 Project Structure

```
IEMS-VCET/
├── frontend/          # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
│   └── package.json
├── backend/           # Node.js + Express API
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── server.js
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js >= 16
- MongoDB Atlas account

### 1. Clone the repository

```bash
git clone https://github.com/913122104047-HARISH-V/IEMS-VCET.git
cd IEMS-VCET
```

### 2. Backend setup

```bash
cd backend
npm install
```

Create `backend/.env`:
```
PORT=5000
MONGODB_URI=your_mongodb_atlas_uri
JWT_SECRET=your_jwt_secret
```

```bash
npm start
```

### 3. Frontend setup

```bash
cd frontend
npm install
npm start
```

---

## 👨‍💻 Team & My Contributions

This project was built as a team of 4 students. My personal contributions included:

- 🔧 Backend REST API development (routes, controllers, middleware)
- 🔐 JWT-based authentication and role-based access control
- 🗄️ MongoDB schema design for users, events, and registrations
- 🔗 Frontend-backend integration (API calls, state management)

---

## 👤 Author

**Harish V** — [GitHub](https://github.com/913122104047-HARISH-V) · [LinkedIn](https://linkedin.com/in/harish-v-a19137265)
