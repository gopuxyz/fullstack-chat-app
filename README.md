# Fullstack Chat App 💬

A real-time fullstack chat application built using the **MERN stack** with **Socket.IO** for live messaging and online status.

---

## 🚀 Features

- 🔐 User Authentication (Signup / Login / Logout)
- 💬 Real-time one-to-one chat using Socket.IO
- 🟢 Online / Offline user status
- 🖼️ Profile picture update
- 🔒 JWT-based authentication
- 🌙 Modern UI with Tailwind CSS
- ⚡ Fast frontend using Vite + React
- ☁️ MongoDB Atlas cloud database

---

## 🛠️ Tech Stack

### Frontend
- React (Vite)
- Zustand (state management)
- Tailwind CSS
- Axios
- Socket.io-client

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- Socket.IO
- JWT Authentication
- bcrypt

---

## 📂 Project Structure

fullstack-chat-app/
├── backend/
│ ├── src/
│ │ ├── controllers/
│ │ ├── middleware/
│ │ ├── models/
│ │ ├── routes/
│ │ └── index.js
│ ├── .env
│ └── package.json
│
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── store/
│ │ └── main.jsx
│ └── package.json
│
├── .gitignore
└── README.md

---

## ⚙️ Environment Variables

Create a `.env` file inside the **backend** folder:

```env
PORT=5001
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
