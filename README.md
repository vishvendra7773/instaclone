

---

# 📸 InstaClone – MERN Stack Social Media App

InstaClone is a full-stack **Instagram-like social media application** built using the **MERN stack**.
It allows users to register, log in, create posts, and interact with content in a modern web interface.

This project demonstrates **full-stack development skills**, RESTful API design, authentication, and database integration.

---

## 🚀 Tech Stack

### Frontend

* React.js
* HTML5, CSS3
* JavaScript
* Axios

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication

### Tools

* NPM
* Git & GitHub
* Postman (API testing)

---

## 📁 Project Structure

```
instaclone/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── index.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
└── README.md
```

---

## ⚙️ Prerequisites

Make sure the following are installed:

* Node.js (v16+ recommended)
* MongoDB (Local or MongoDB Atlas)
* Git

---

## 🔐 Backend Environment Variables

Create a `.env` file inside the **backend** directory:

```
backend/.env
```

Add the following:

```env
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/instaclone
JWT_SECRET=your_secret_key
```

⚠️ **Do not upload `.env` to GitHub**

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Surendrakumarpatel/instaclone.git
cd instaclone
```

---

### 2️⃣ Run Backend Server

```bash
cd backend
npm install
npm start
```

Backend runs at:

```
http://localhost:5000
```

✔ MongoDB must be running
✔ `.env` must be correctly configured

---

### 3️⃣ Run Frontend

Open a **new terminal**:

```bash
cd frontend
npm install
npm start
```

Frontend runs at:

```
http://localhost:3000
```

---

## 🔄 API Base URL

```
http://localhost:5000/api
```

You can test APIs using **Postman**.

---

## 🧪 Common Errors & Fixes

### ❌ Mongoose URI Undefined

**Cause:** `.env` missing or variable name incorrect
**Fix:** Ensure `MONGO_URI` exists and `dotenv` is used:

```js
import dotenv from "dotenv";
dotenv.config();
```

---

### ❌ Port Already in Use

Change the port in `.env`:

```env
PORT=5001
```

---

## 🌟 Features

* User Authentication (JWT)
* Create and View Posts
* Image Upload Support
* RESTful APIs
* Clean and Modular Code Structure

---

## 🚧 Future Improvements

* Like & Comment System
* Follow / Unfollow Users
* User Profiles
* Real-time Notifications
* Deployment (AWS / Vercel)

---

## 👨‍💻 Author

**Akshat Totla**
B.Tech | Full-Stack Developer
Skills: JavaScript, Node.js, React, MongoDB, Java, Spring Boot

---

## ⭐ Support

If you find this project helpful, please ⭐ the repository.

---

