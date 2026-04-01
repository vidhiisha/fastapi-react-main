# 🚀 FastAPI + React Full Stack Application

## 📌 Overview

This project is a full-stack web application built using **FastAPI (Python)** for the backend and **React (Vite)** for the frontend. It demonstrates how modern web applications handle client-server communication using REST APIs.

The application allows users to perform basic **CRUD (Create, Read, Update, Delete)** operations through an interactive UI.

---

## 🎯 Features

* 🔗 Integration of React frontend with FastAPI backend
* 📡 REST API communication
* 📝 Create, Read, Update, Delete functionality
* ⚡ Fast backend using FastAPI
* 🎨 Interactive frontend using React (Vite)
* 📘 API testing with Swagger UI

---

## 🧰 Tech Stack

### Frontend:

* React (Vite)
* JavaScript
* Axios

### Backend:

* FastAPI (Python)
* Uvicorn

---

## 📁 Project Structure

```
fastapi-react/
│
├── backend/        # FastAPI backend
│   ├── app/
│   │   └── api.py  # Main API file
│   └── main.py     # Entry point
│
├── frontend/       # React frontend
│   ├── src/
│   └── package.json
│
└── README.md
```

## 🔹 Run Backend

```bash
cd backend
python -m pip install fastapi uvicorn
python main.py
```

👉 Backend will run at:
http://127.0.0.1:8000

👉 Swagger Docs:
http://127.0.0.1:8000/docs

---

## 🔹 Run Frontend

```bash
cd frontend
npm install
npm run dev
```

👉 Frontend will run at:
http://localhost:5173

---

## ❗ Important Notes

* Do **NOT** open `0.0.0.0:8000` in browser

* Always use:

  * `http://127.0.0.1:8000`
  * or `http://localhost:8000`

* Make sure **Node.js version ≥ 18**

---

## 🔄 API Endpoints (Example)

| Method | Endpoint    | Description     |
| ------ | ----------- | --------------- |
| GET    | /           | Welcome message |
| GET    | /todos      | Fetch all tasks |
| POST   | /todos      | Create new task |
| PUT    | /todos/{id} | Update task     |
| DELETE | /todos/{id} | Delete task     |

---

## 🧠 Learning Outcomes

* Understanding full-stack architecture
* Connecting React frontend with FastAPI backend
* Working with REST APIs
* Debugging real-world setup issues
* Running modern frontend using Vite

---

## 🚧 Future Improvements

* Add database (MongoDB / PostgreSQL)
* Implement authentication (JWT)
* Improve UI/UX
* Add real-time features

---

## 👩‍💻 Author

Vidhi

---

## 📜 License

This project is open-source and available under the MIT License.

