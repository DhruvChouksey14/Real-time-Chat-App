# Real-time-Chat-App

Live Demo : https://real-time-chat-app-5dqr.onrender.com/login

# 🚀 Chat App



A powerful real-time chat application with authentication, theming, and media sharing.

## 🌟 Features
- **Real-Time Messaging** 📩
- **User Authentication** 🔐 (JWT-based login & signup)
- **Theming (Zustand + DaisyUI)** 🌗 (DaisyUI themes with Zustand state management where you can change theme according to your preference)
- **Online Status Indicator** 🟢
- **Profile Customization** 🖼️
- **Cloudinary Integration** ☁️ (Image Upload & Sharing)
- **Responsive UI** 📱 (Tailwind CSS)

---

## 📸 Screenshots
### 🏠 Home Page
![Home Page](./screenshot/home.png)

### 🔐 Login Page
![Login Page](./screenshot/login.png)

### 📜 Chat Interface
![Chat Interface](./screenshot/chat.png)

---

## 🛠️ Tech Stack
- **Frontend:** React, Tailwind CSS, DaisyUI, Zustand
- **Backend:** Node.js, Express.js, MongoDB
- **Authentication:** JWT
- **Storage:** Cloudinary
- **Real-time:** WebSockets (Socket.io)

---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```sh
git clone https://github.com/your-username/chat-app.git
cd chat-app
```

### 2️⃣ Set up the environment variables
Create a `.env` file in the **backend** directory and add:
```env
MONGODB_URI=your_mongo_uri_here
PORT=5001
JWT_SECRET=your_jwt_secret_here
CLOUDINARY_CLOUD_NAME=your_cloud_name_here
CLOUDINARY_API_KEY=your_api_key_here
CLOUDINARY_API_SECRET=your_api_secret_here
NODE_ENV=development
```

### 3️⃣ Install dependencies
#### Frontend:
```sh
cd frontend
npm install
```

#### Backend:
```sh
cd backend
npm install
```

### 4️⃣ Start the application
#### Run backend:
```sh
cd backend
npm start
```

#### Run frontend:
```sh
cd frontend
npm run dev
```

Now visit **http://localhost:5173/** to see your app in action! 🎉

---

## 📌 Theming (Zustand + DaisyUI)
- Default theme: `coffee`
- Change theme via Zustand `useThemeStore`
- Saves user preference in `localStorage`

---



