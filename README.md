# 🚀 PingMe – Real-Time Chat Application

PingMe is a modern **full-stack real-time chat application** that allows users to connect, send messages instantly, and share images in a smooth and responsive interface.
The project is built using **React, Node.js, Express, MongoDB, and Socket.io** to deliver fast and scalable real-time communication.

---
<p align="center">
  <img src="frontend/public/screenshot-for-readme.png.png" width="900"/>
</p>

## ✨ Key Features

* 🔐 **Secure JWT Authentication** (Custom authentication system)
* 💬 **Real-time messaging** powered by Socket.io
* 🟢 **Online / Offline user status indicators**
* 🔔 **Typing and notification sounds**
* 📨 **Automatic welcome email on signup**
* 🖼️ **Image sharing support** using Cloudinary
* 🚦 **API Rate Limiting** for improved security
* 🎨 **Modern UI** built with React, Tailwind CSS, and DaisyUI
* ⚡ **Fast REST API** using Node.js and Express
* 🧠 **Efficient state management** with Zustand
* 🗄️ **MongoDB database** for storing users and chat messages

---

## 🛠️ Tech Stack

### Frontend

* React
* Tailwind CSS
* DaisyUI
* Zustand
* Socket.io Client

### Backend

* Node.js
* Express.js
* MongoDB
* Socket.io
* JWT Authentication

### External Services

* Cloudinary (Image Storage)
* Resend (Email Service)

---

## 📂 Project Structure

```id="ag2r1k"
PingMe
│
├── backend
│   ├── controllers
│   ├── routes
│   ├── models
│   └── server.js
│
└── frontend
    ├── components
    ├── pages
    └── main.jsx
```

---

## ⚙️ Environment Variables

Create a `.env` file inside the **backend folder** and add the following:

```id="0pizsf"
PORT=3000
MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

RESEND_API_KEY=your_resend_api_key

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

---

## ▶️ Running the Project Locally

### 1️⃣ Start the Backend

```id="4b94jn"
cd backend
npm install
npm run dev
```

### 2️⃣ Start the Frontend

```id="5xv6ec"
cd frontend
npm install
npm run dev
```

---

Example:

* Login Page
* Chat Interface
* Image Sharing

---

## 👨‍💻 Author

**Utkarsh Johari**

If you found this project helpful, consider giving it a ⭐ on GitHub.
