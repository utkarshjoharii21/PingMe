# 🚀 PingMe – Real-Time Chat Application

![PingMe Preview](frontend/public/screenshot-for-readme.png.png)
## 🛠️ Tech Stack
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON-web-tokens&logoColor=white)

PingMe is a modern **full-stack real-time chat application** that allows users to connect, send messages instantly, and share images in a smooth and responsive interface.
The project is built using **React, Node.js, Express, MongoDB, and Socket.io** to deliver fast and scalable real-time communication.

---

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
