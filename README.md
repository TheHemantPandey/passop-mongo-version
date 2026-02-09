# 🔐 PassOP — MongoDB Full-Stack Password Manager

![React](https://img.shields.io/badge/React-blue)
![Node.js](https://img.shields.io/badge/Node.js-green)
![Express](https://img.shields.io/badge/Express-black)
![MongoDB](https://img.shields.io/badge/MongoDB-darkgreen)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-skyblue)
![Vercel](https://img.shields.io/badge/Deployed-Vercel-brightgreen)

---

## 📌 Overview

**PassOP Mongo Version** is an advanced **Full-Stack Password Manager Application** built using the **MERN Stack**.  
Unlike the localStorage version, this version stores passwords securely in a **MongoDB Database** using a backend API.

This project demonstrates real-world full-stack development skills including database integration, REST APIs, and scalable architecture.

---

## 📸 Project Preview

![PassOP Mongo Screenshot]<img width="1600" height="876" alt="image" src="https://github.com/user-attachments/assets/903ce4b0-5a0f-499a-9078-9ad3f2bfc813" />


---





## ✨ Features

- ✅ Full CRUD Operations (Create, Read, Update, Delete)
- ✅ Passwords stored securely in MongoDB
- ✅ RESTful API built with Express.js + Node.js
- ✅ Modern responsive UI using React + Tailwind CSS
- ✅ Toast Notifications for actions
- ✅ Scalable Full-Stack Folder Structure

---

## 🛠️ Tech Stack

### Frontend
- React.js (Vite)
- Tailwind CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB (Local or Atlas)

---

## 🌍 LocalStorage Version (Deployed)

A simpler frontend-only version is also available and deployed live:

🚀 **Live Demo:** https://passop-by-hemant.vercel.app/  
📌 **Repository:** https://github.com/TheHemantPandey/passop-password-manager

---

## ⚙️ Setup Instructions (Run Locally)

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/TheHemantPandey/passop-mongo-version.git
```

### 2️⃣ Go Inside the Project Folder

```bash
cd passop-mongo-version
```

---

## 🔧 Backend Setup

### 3️⃣ Install Dependencies

```bash
npm install
```

### 4️⃣ Configure Environment Variables

Create a `.env` file in the root directory:

```env
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

---

### 5️⃣ Start Backend Server

```bash
npm start
```

Backend will run on:

```
http://localhost:5000
```

---

## 🎨 Frontend Setup

If frontend is inside a separate folder:

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on:

```
http://localhost:5173
```

---

## 📡 API Endpoints

| Method | Endpoint         | Description              |
|--------|------------------|--------------------------|
| GET    | `/api/passwords` | Fetch all passwords      |
| POST   | `/api/passwords` | Add a new password       |
| PUT    | `/api/passwords` | Update an existing entry |
| DELETE | `/api/passwords` | Delete a password        |

---

## 📂 Project Structure

```bash
passop-mongo-version/
 ┣ backend/
 ┃ ┣ server.js
 ┃ ┣ routes/
 ┃ ┣ models/
 ┃ ┗ config/
 ┣ frontend/
 ┃ ┣ src/
 ┃ ┣ components/
 ┃ ┗ App.jsx
 ┣ .env.example
 ┣ package.json
 ┗ README.md
```

---

## 🌟 Future Enhancements

- 🔒 Authentication & User Accounts
- 🔑 Password Encryption
- ☁️ Deployment with MongoDB Atlas + Render
- 📱 Improved Mobile UI

---

## 👨‍💻 Author

**Hemant Pandey**  
Full Stack Developer (MERN + Next.js)

- GitHub: https://github.com/TheHemantPandey  
- LinkedIn: https://linkedin.com/in/hemant-pandey-ase  

---

## 📄 License

This project is open-source under the **MIT License**.
