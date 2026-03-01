# Realtime Chat App

Welcome to the **Realtime Chat App**, a full-stack, responsive messaging platform built with modern web technologies! Enjoy seamless real-time communication, customizable themes, secure authentication, and a lightning-fast user experience. 

🚀 **Live Demo:** [https://realtime-chat-app-75ha.onrender.com](https://realtime-chat-app-75ha.onrender.com)

---

## ✨ Features

- **Real-Time Messaging**: Built on Socket.io for instantaneous message delivery with zero delay.
- **Secure Authentication**: Robust JWT-based authentication system with secure cookies.
- **Dynamic Themes**: Beautiful and customizable UI elements powered by DaisyUI. Choose your favorite look!
- **Image Sharing**: Easily upload and share images using Cloudinary integration.
- **Online Status**: See when your friends are online in real-time.
- **Responsive Design**: Flawless experience across all devices, from desktops to mobile phones.
- **State Management**: Highly optimized state management handled by Zustand.

---

## 🛠️ Tech Stack

### Frontend
- **React 18**: Component-based UI rendering.
- **Vite**: Ultra-fast frontend build tooling.
- **TailwindCSS & DaisyUI**: Rapid styling with beautiful, customizable utility classes and components.
- **Zustand**: Lightweight and fast global state management.
- **Socket.io-client**: Real-time websocket connectivity.
- **React Router Dom**: Smooth single-page application navigation.
- **Axios**: Promised-based HTTP client for API requests.

### Backend
- **Node.js & Express**: High-performance javascript runtime and server framework.
- **MongoDB & Mongoose**: Flexible NoSQL database with elegant object modeling.
- **Socket.io**: Real-time event-based communication engine.
- **Cloudinary**: Cloud-based image and video management services.
- **JSON Web Tokens (JWT)**: Secure stateless authentication mechanism.
- **Bcryptjs**: Industry-standard password hashing.

---

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

You will need the following installed on your machine:
- Node.js (v18+ recommended)
- npm or yarn
- MongoDB account/connection URI
- Cloudinary account for managing image uploads

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AMIT6743/Realtime-Chat-App.git
   cd Realtime-Chat-App
   ```

2. **Install Backend Dependencies:**
   ```bash
   cd backend
   npm install
   ```

3. **Install Frontend Dependencies:**
   ```bash
   cd ../frontend
   npm install
   ```

### Configuration

Create a `.env` file inside the `backend/` directory with the following environment variables:

```env
# Server Port
PORT=5001

# MongoDB Connection String
MONGODB_URI=your_mongodb_connection_string

# JWT Secret Key
JWT_SECRET=your_super_secret_jwt_key

# Cloudinary Configuration
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

# Environment (development or production)
NODE_ENV=development
```

### Running the Application

1. **Start the backend server (Development):**
   ```bash
   cd backend
   npm run dev
   ```

2. **Start the frontend application:**
   ```bash
   cd frontend
   npm run dev
   ```

3. Open your browser and navigate to `http://localhost:5173`.

---

## 🌐 Deployment (Render)

This project is configured to be easily deployed on Render as a single web service.

The root `package.json` includes custom scripts to build both the frontend and backend simultaneously.

1. Create a **Web Service** on Render hooked up to your GitHub repository.
2. Set the **Build Command** to: `npm run build`
3. Set the **Start Command** to: `npm start`
4. Add all environment variables found in your local `.env`. Ensure `NODE_ENV` is set to `production`.

---
*Created with ❤️ by Amit.*
