# Realtime Chat App

A realtime chat application built with **Node.js, Express, Socket.io** on the backend and **React, Vite, Tailwind CSS** on the frontend.  
This app enables users to send and receive messages instantly with authentication, message storage, and live updates.  

## ✨ Features
- 🔐 **User Authentication** (Sign up, Login)  
- 💬 **Realtime Messaging** using Socket.io  
- 📂 **Message & User Models** with database integration  
- ☁️ **Cloudinary integration** for media uploads (images, files)  
- 🛡️ **Authentication Middleware** to protect routes  
- 🎨 **Frontend** built with React + Tailwind + Vite  
- 📱 **Modern UI** with loading skeletons and responsive design  
- 🚀 **Deployment** via Vercel (frontend live)  

## 🗂️ Project Structure

### Backend
```
backend/
├── src/
│   ├── controllers/
│   │   ├── auth.controller.js
│   │   └── message.controller.js
│   ├── lib/
│   │   ├── cloudinary.js
│   │   ├── db.js
│   │   ├── socket.js
│   │   └── utils.js
│   ├── middleware/
│   │   └── auth.middleware.js
│   ├── models/
│   │   ├── message.model.js
│   │   └── user.model.js
│   ├── routes/
│   │   ├── auth.route.js
│   │   └── message.route.js
│   ├── seeds/
│   │   └── user.seed.js
│   └── index.js
```

### Frontend
```
frontend/
├── public/
│   ├── avatar.png
│   ├── screenshot-for-readme.png
│   └── vite.svg
├── src/
│   ├── components/
│   │   ├── AuthImagePattern.jsx
│   │   ├── ChatContainer.jsx
│   │   ├── ChatHeader.jsx
│   │   ├── MessageInput.jsx
│   │   ├── Navbar.jsx
│   │   ├── NoChatSelected.jsx
│   │   ├── Sidebar.jsx
│   │   └── skeletons/
│   │       ├── MessageSkeleton.jsx
│   │       └── SidebarSkeleton.jsx
│   ├── constants/
│   │   └── index.js
│   ├── lib/
│   │   ├── axios.js
│   │   └── utils.js
│   ├── pages/
│   │   ├── HomePage.jsx
│   │   ├── LoginPage.jsx
│   │   ├── ProfilePage.jsx
│   │   ├── SettingsPage.jsx
│   │   └── SignUpPage.jsx
│   └── store/
│       ├── useAuthStore.js
│       ├── useChatStore.js
│       └── useThemeStore.js
├── index.html
├── package.json
├── vite.config.js
├── tailwind.config.js
└── vercel.json
```

🛠️ Tech Stack

Frontend: React, Vite, Tailwind CSS, Zustand (state management)
Backend: Node.js, Express.js, Socket.io
Database: MongoDB (planned)
Media Storage: Cloudinary
Deployment: Vercel (frontend)


🚀 Usage
1. Clone the repository:
```git clone https://github.com/your-username/realtime-chat-app.git```
2. Navigate to frontend:
```
cd frontend
npm install
npm run dev
```
3. (Optional, once backend is ready) Navigate to backend:
   ```
   cd backend
   npm install
   npm run dev
   ```
🌐 Live Demo
Frontend is live here: [Chat App](chat-app-pink-sigma-34.vercel.app) (Login Page)


