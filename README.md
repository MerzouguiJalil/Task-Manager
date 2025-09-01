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

![Node.js](https://img.shields.io/badge/Node.js-18-green?logo=node.js)  
![Express.js](https://img.shields.io/badge/Express.js-Backend-black?logo=express)  
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green?logo=mongodb)  
![JWT](https://img.shields.io/badge/JWT-Authentication-blue?logo=jsonwebtokens)  

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
⚙️ Installation
Clone the repository

bash
Copier le code
git clone https://github.com/your-username/task-manager.git
cd task-manager
Install dependencies

bash
Copier le code
npm install
Create a .env file and add:

env
Copier le code
PORT=3000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
Start the server

bash
Copier le code
npm run dev
📌 API Endpoints
Auth
POST /users → Register

POST /users/login → Login

POST /users/logout → Logout

Tasks
POST /tasks → Create task

GET /tasks → Get all tasks

PATCH /tasks/:id → Update task

DELETE /tasks/:id → Delete task

📸 Screenshots
(Add a screenshot or GIF of your API in Postman or frontend if you build one)

🚀 Future Improvements
Add a frontend (React / Next.js)

Add task categories & priorities

Add reminders & notifications

Deploy on Render / Railway

