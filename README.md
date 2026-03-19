# Task Manager API 🚀

A RESTful API built using **Node.js, Express, and MongoDB**, deployed live on Render.

---

## 🌐 Live API

Base URL:
https://task-manager-api-82hj.onrender.com

---

## 🚀 Features

- Create Task  
- Get All Tasks  
- Update Task  
- Delete Task  
- Filter Tasks (completed / pending)  

---

## 🛠️ Tech Stack

- Node.js  
- Express.js  
- MongoDB Atlas  
- Mongoose  
- Render (Deployment)  

---

## 📌 API Endpoints

| Method | Endpoint | Description |
|--------|---------|------------|
| POST | /api/tasks | Create task |
| GET | /api/tasks | Get all tasks |
| GET | /api/tasks?status=completed | Filter tasks |
| PUT | /api/tasks/:id | Update task |
| DELETE | /api/tasks/:id | Delete task |

---

## 🧪 Example Request

### Create Task

```json
{
  "title": "Learn Backend",
  "description": "Build API project"
}
