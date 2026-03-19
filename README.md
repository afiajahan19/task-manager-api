# Task Manager API 🚀

A RESTful API built using Node.js, Express, and MongoDB.

## Features
- Create Task
- Get All Tasks
- Update Task
- Delete Task
- Filter Tasks (completed / pending)

## Tech Stack
- Node.js
- Express.js
- MongoDB
- Mongoose

## API Endpoints

| Method | Endpoint | Description |
|--------|---------|------------|
| POST | /api/tasks | Create task |
| GET | /api/tasks | Get all tasks |
| GET | /api/tasks?status=completed | Filter tasks |
| PUT | /api/tasks/:id | Update task |
| DELETE | /api/tasks/:id | Delete task |

## Run Locally

```bash
npm install
npx nodemon server.js


---

## ✅ 3. Push Changes Again

```bash id="m2k8dj"
git add .
git commit -m "Added README and gitignore"
git push
