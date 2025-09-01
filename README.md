# 📌 Task Manager App  

A simple and powerful **Task Manager** built with **Node.js, Express, and MongoDB**.  
This app lets users create, update, and delete tasks with authentication support.  

---

## 🚀 Features  
- 🔑 **User Authentication** (Sign Up / Sign In with JWT)  
- 📋 **CRUD Operations** (Create, Read, Update, Delete tasks)  
- ✅ **Mark tasks as complete/incomplete**  
- 🔒 **Secure Passwords** (hashed with bcrypt)  
- 🌐 **RESTful API** structure  
- 📊 **MongoDB Atlas / Local MongoDB support**  

---

## 🛠️ Tech Stack  

<p align="left">
  <a href="https://nodejs.org/" target="_blank">
    <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white"/>
  </a>
  <a href="https://expressjs.com/" target="_blank">
    <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white"/>
  </a>
  <a href="https://www.mongodb.com/" target="_blank">
    <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
  </a>
  <a href="https://jwt.io/" target="_blank">
    <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white"/>
  </a>
</p>

---

## 📂 Project Structure  

```bash
task-manager/
│── src/
│   ├── index.js        # Entry point
│   ├── db/mongoose.js  # MongoDB connection
│   ├── models/         # Mongoose models
│   ├── routers/        # Express routes
│   └── middleware/     # Auth middleware
│
│── .env                # Environment variables
│── package.json
│── README.md
