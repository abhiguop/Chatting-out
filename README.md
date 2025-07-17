# 💬 Chatting Out

A real-time chat app built using **MERN Stack** and **Socket.IO**.


## 🚀 Features
- Real-time messaging (Socket.IO)
- JWT authentication
- Online user status
- Notifications
- Search & chat with users
- Responsive UI (Tailwind CSS)

## 🛠️ Tech Stack
**Frontend:** React, Tailwind CSS, Axios  
**Backend:** Node.js, Express, MongoDB, Mongoose  
**Auth:** JWT, bcryptjs  
**Realtime:** Socket.IO

## ⚙️ Prerequisites
- Node.js v16+
- MongoDB
- npm or yarn

## 📦 Setup

### Backend
```bash
cd server
npm install
# .env setup:
# PORT=5000
# MONGO_URI=<your_mongo_uri>
# JWT_SECRET=<your_secret>
npm run dev

## Frontend
cd client
npm install
# .env setup:
# REACT_APP_API_URL=http://localhost:5000
npm start

