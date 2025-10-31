# 🎥 Streamify — Real-Time Video Calling & Chat Application (MERN Stack)

## 🧭 Overview

Streamify is a production-grade, real-time video calling and chat platform built using the MERN stack (MongoDB, Express.js, React.js, Node.js). 
It enables users to connect instantly through video calls, chats, and reactions, with built-in authentication, theming, and real-time updates in a single modern web app.
Designed as a language-exchange and communication platform, Streamify allows users to chat, call, and connect with friends through one-on-one or group video calls, real-time messaging, and interactive UI themes.
The project showcases advanced full-stack development principles, including custom hooks and real-time synchronization using production-ready patterns for a seamless and engaging experience.

🔗 Live demo: https://streamify-social-app-vo9h.onrender.com

---

## ⚙️ Key Features

### 🧑‍💻 User Experience
- 🔐 **JWT-based Authentication** – Secure login and signup system.
- 🧭 **Onboarding Flow** – Smooth user setup and profile creation.
- 👥 **Friends System** – Send, accept, or decline friend requests.
- 💬 **Real-Time Chat** – Typing indicators, message threads, image uploads, and reactions.
- 📹 **Video Calling** – One-to-one or group video calls with:
  - Screen sharing  
  - Reactions  
  - Call recording  
- 🎨 **32 Custom UI Themes** – Personalize your interface instantly.
- 🚨 **Protected Routes** – Secure access to private pages.
- 🧪 **API Testing** – Reliable and well-tested endpoints.

---

## 🧰 Tech Stack

| Layer | Technologies |
|-------|---------------|
| **Frontend** | React.js, TanStack Query, Tailwind CSS |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB |
| **Authentication** | JWT (JSON Web Tokens) |
| **Real-Time Services** | Stream API |
| **Deployment** | Render (Backend & Frontend), MongoDB Atlas |

---

**🚀 Installation Guide**

Prerequisites
  - Node.js (16+ recommended)
  - MongoDB (local or Atlas)
  - Cloudinary or object storage account (optional)
  - GetStream / WebRTC credentials (if using Stream)
  - Yarn or npm


Follow these steps to set up the project locally.

  1️⃣ Clone the Repository
  
    git clone https://github.com/yourusername/streamify.git
    cd streamify

  2️⃣ Install Dependencies
  
    Backend:
      cd backend
      npm install

    Frontend:
      cd ../frontend
      npm install

  3️⃣ Environment Variables
  
    Create a .env file in your backend folder with:
      PORT=5000
      MONGO_URI=your_mongodb_connection_string
      JWT_SECRET=your_jwt_secret
      STREAM_API_KEY=your_stream_api_key
      STREAM_API_SECRET=your_stream_api_secret
  
  4️⃣ Run the Application
  
    Backend:
      cd backend
      npm run dev
    
    Frontend:
      cd ../frontend
      npm start

    Then open your browser and visit:
      http://localhost:5001

---

**🗂️ Folder Structure**

    streamify/
    │
    ├── backend/
    |   ├── src/
    │   |    ├── controllers/
    |   |    ├── lib/
    │   |    ├── models/
    │   |    ├── routes/
    │   |    ├── middleware/
    │   |    └── server.js
    │   ├── .env
    |   └── ....
    |
    ├── frontend/
    │   ├── src/
    |   |   ├── assets
    │   │   ├── components/
    |   |   ├── constants/
    │   │   ├── pages/
    │   │   ├── hooks/
    │   │   ├── lib/
    |   |   ├── store?
    │   │   ├── App.js
    |   |   └── main.jsx
    |   |
    │   ├── package.json
    │   └── ....
    |
    └── README.md

---

**🧪 Testing**

  * Use Postman or Insomnia to test endpoints.
  * Backend unit/integration tests via Jest / Supertest

---

**📦 Deployment**

  🔗 Live App: https://streamify-social-app-vo9h.onrender.com

---

**🧩 Future Enhancements**

    📱 Mobile version (React Native / Flutter)
    🧠 AI-based conversation suggestions
    🌍 Multi-language support
    🔔 Push notifications
    🕵️‍♂️ End-to-end message encryption

---

**👨‍💻 Author**

    Samith Shashika
    GitHub: https://github.com/SamithShashika71
    G-mail: samithsashika71@gmail.com

 ---

**🪪 License**
  
  This project is licensed under the MIT License — free to use, modify, and distribute.

