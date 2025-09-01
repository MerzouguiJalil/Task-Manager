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

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="50" height="50"/> &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" width="50" height="50"/> &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" width="50" height="50"/> &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="50" height="50"/> &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="50" height="50"/>
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
