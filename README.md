# 💬 TappIn – Real-Time Chat Application

TappIn is a full-stack **real-time chat application** built using the **MERN stack** that enables users to connect, chat instantly, and share images in a modern and responsive interface.

---

## 🚀 Features

* 💬 Real-time messaging
* 👤 User authentication & sessions
* 🟢 Online / Offline status
* 🔍 Search users
* 🧾 Chat history
* 📎 Media sharing (images)
* 🎨 Modern UI with smooth UX
* 🔐 Secure backend APIs

---

## 🖥️ Tech Stack

**Frontend:**

* React.js (Vite)
* CSS / Tailwind (if used)

**Backend:**

* Node.js
* Express.js

**Database:**

* MongoDB (MongoDB Atlas recommended)

**Real-time Communication:**

* Socket.IO

---

## 📂 Project Structure

```id="v8hz3x"
TappIn-App/
│
├── client/        # Frontend (React + Vite)
├── server/        # Backend (Node + Express + Socket.IO)
├── README.md
```

---

## ⚙️ Setup Instructions (Local Development)

### 1️⃣ Clone Repository

```id="l3pfzt"
git clone https://github.com/ujwal1456/TappIn-App.git
cd TappIn-App
```

---

### 2️⃣ Setup Backend

```id="n2y8v1"
cd server
npm install
```

Create `.env` file inside `server/`:

```id="7g5k1o"
MONGODB_URI = <your_mongodb_string>
PORT=5000
JWT_SECRET=<your_jwt_secret>

CLOUDINARY_CLOUD_NAME = <your_cloudinary_name>
CLOUDINARY_API_KEY= <your_cloudinary_api_key>
CLOUDINARY_API_SECRET= <your_cloudinary_api_secret>

```

Run backend:

```id="9k2f8w"
node server.js
```

---

### 3️⃣ Setup Frontend

Create `.env` file inside `client/`:

```id="7g5k1o"
VITE_BACKEND_URL = 'http://localhost:5000'
```


Open a new terminal:

```id="0x9d5b"
cd client
npm install
npm run dev
```

---

## 🌐 Application URLs

| Service  | URL                   |
| -------- | --------------------- |
| Frontend | http://localhost:5173 |
| Backend  | http://localhost:5000 |

---

## 🔗 API & Socket Configuration

Ensure frontend connects to backend:

```id="c8m2v6"
const API_URL = "http://localhost:5000";
const SOCKET_URL = "http://localhost:5000";
```

---

---

---

## ⚠️ Notes

* Backend must be running before frontend
* MongoDB connection is required
* `.env` should not be committed

---

## 👨‍💻 Author

* Periketi Ujwal

---

## 📜 License

This project is for educational purposes.
