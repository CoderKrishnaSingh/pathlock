# 💼 Full-Stack Project Showcase

This repository features two full-stack web applications built using **React + TypeScript** for the frontend and **.NET 8 Web API (C#)** for the backend.
Each project demonstrates key aspects of modern full-stack development — from REST APIs to responsive UI and authentication.

---

## 🧠 Projects Overview

| Project                  | Description                                                                           | Tech Stack                                               |
| ------------------------ | ------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| **Basic Task Manager**   | A simple task management app for adding, viewing, toggling, and deleting tasks.       | React, TypeScript, TailwindCSS, .NET 8                   |
| **Mini Project Manager** | A project management app with JWT authentication, project CRUD, and smart scheduling. | React, TailwindCSS, ASP.NET Core, JWT, SQLite/PostgreSQL |

---

# 🧠 Basic Task Manager

A **full-stack web application** built with **React + TypeScript** for the frontend and **.NET 8 Web API (C#)** for the backend.
This app allows users to create, view, toggle, and delete tasks with a clean and responsive interface.

---

## 🚀 Features

* ✅ Add new tasks with descriptions
* 📝 View all tasks in a dynamic list
* 🔄 Toggle tasks between **Completed** and **Active**
* ❌ Delete tasks instantly
* 🔍 Filter tasks by **All / Active / Completed**
* 💾 Tasks stored in **memory** and cached in **localStorage**
* 🎨 Responsive design using **Tailwind CSS**

---

## 🛠️ Tech Stack

| Layer        | Technology                                   |
| ------------ | -------------------------------------------- |
| **Frontend** | React, TypeScript, Axios, TailwindCSS, Vite  |
| **Backend**  | .NET 8, C#, ASP.NET Core Web API             |
| **Tools**    | Visual Studio Code, PowerShell, Git & GitHub |

---

## ⚙️ Project Structure

```
basic-task-manager/
│
├── backend-dotnet/
│   ├── Controllers/
│   │   └── TasksController.cs
│   ├── Program.cs
│   ├── appsettings.json
│   └── backend-dotnet.csproj
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── AddTaskForm.tsx
│   │   │   └── TaskList.tsx
│   │   ├── api.ts
│   │   ├── App.tsx
│   │   └── main.tsx
│   ├── vite.config.ts
│   ├── package.json
│   └── tailwind.config.js
│
├── .gitignore
└── README.md
```

---

## 🧩 API Endpoints

| Method     | Endpoint                 | Description            |
| ---------- | ------------------------ | ---------------------- |
| **GET**    | `/api/tasks`             | Get all tasks          |
| **POST**   | `/api/tasks`             | Create a new task      |
| **PATCH**  | `/api/tasks/{id}/toggle` | Toggle task completion |
| **DELETE** | `/api/tasks/{id}`        | Delete a task          |

---

## 🖥️ How to Run Locally

### 1️⃣ Run Backend

```bash
cd backend-dotnet
dotnet run
```

Runs backend on: **[http://localhost:5097](http://localhost:5097)**

### 2️⃣ Run Frontend

```bash
cd frontend
npm install
npm run dev
```

Frontend: **[http://localhost:3000](http://localhost:3000)**

---

## 🧠 Future Improvements

* Persistent storage (SQLite / PostgreSQL)
* JWT authentication
* Editable task descriptions
* Dockerized full-stack deployment

---

# 🌞 Mini Project Manager

A simple, full-stack **Project Management Web App** to create, organize, and track projects — built with **ASP.NET Core**, **React**, and **TailwindCSS**.

---

## ✨ Features

* 🔐 **JWT-based authentication** (Register & Login)
* 📁 **Create, edit, and delete projects**
* 🧠 **Smart project scheduling** with automated stages
* ⚡ **Real-time UI feedback** (loaders & notifications)
* 📱 **Fully responsive** design
* ☁️ **Backend on Render**, **Frontend on Vercel**

---

## 🛠️ Tech Stack

| Layer              | Technology                           |
| ------------------ | ------------------------------------ |
| **Frontend**       | React + Vite + TailwindCSS           |
| **Backend**        | ASP.NET Core Web API                 |
| **Database**       | SQLite (local) / PostgreSQL (Render) |
| **Authentication** | JWT (JSON Web Tokens)                |
| **Hosting**        | Render (Backend) + Vercel (Frontend) |

---

## ⚙️ Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/krishnasingh24/mini-project-manager.git
cd mini-project-manager
```

### 2️⃣ Backend Setup

```bash
cd backend
dotnet restore
dotnet run
```

Backend runs on **[http://localhost:5097](http://localhost:5097)**

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on **[http://localhost:3000](http://localhost:3000)**

---

## 🔐 Environment Variables

### Backend (.NET)

```bash
JWT_SECRET=your_jwt_secret_key
DB_CONNECTION=your_database_connection_string
```

### Frontend

```bash
VITE_API_BASE_URL=http://localhost:5097/api
```

---

## 📂 Folder Structure

```
mini-project-manager/
│
├── backend/
│   ├── Controllers/
│   ├── Models/
│   ├── Services/
│   ├── Program.cs
│   ├── appsettings.json
│   └── mini-project-manager.csproj
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── api/
│   │   ├── App.tsx
│   │   └── main.tsx
│   ├── vite.config.ts
│   ├── package.json
│   └── tailwind.config.js
│
└── README.md
```

---

## 🧩 API Endpoints

| Method     | Endpoint             | Description             |
| ---------- | -------------------- | ----------------------- |
| **POST**   | `/api/auth/register` | Register new user       |
| **POST**   | `/api/auth/login`    | Login and get JWT token |
| **GET**    | `/api/projects`      | Get all projects        |
| **POST**   | `/api/projects`      | Create a new project    |
| **PUT**    | `/api/projects/{id}` | Update a project        |
| **DELETE** | `/api/projects/{id}` | Delete a project        |

---

## 🎨 Demo

🔗 **Frontend (Vercel)** → [https://mini-project-manager.vercel.app](https://mini-project-manager.vercel.app)
🔗 **Backend (Render)** → [https://mini-project-manager-api.onrender.com](https://mini-project-manager-api.onrender.com)

---

## 🧠 Future Enhancements

* 📅 Gantt chart visualization for project timelines
* 👥 Team collaboration & role-based access
* 🔔 Email notifications and reminders
* 🐳 Docker-based full-stack deployment

---

# 👨‍💻 Author

**Krishna Singh**
Full-Stack Developer | Electrical Engineering (B.Tech)
📧 [GitHub Profile](https://github.com/krishnasingh24)

---


