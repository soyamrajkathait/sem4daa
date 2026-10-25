# 📅 Timetable Generator

An automated timetable scheduling system built using **Python**, **FastAPI**, and **HTML/CSS/JavaScript** that generates conflict-free class schedules for educational institutions. The system uses a hybrid **Greedy + Backtracking** scheduling algorithm with graph-based conflict detection to efficiently allocate teachers, classrooms, and sections.

---

## 🚀 Features

- 📚 Automated timetable generation
- 👨‍🏫 Prevents teacher scheduling conflicts
- 🏫 Prevents classroom allocation conflicts
- 👥 Prevents section timing conflicts
- ⚡ Hybrid Greedy + Backtracking scheduling algorithm
- 🌐 RESTful APIs built with FastAPI
- ✅ Request validation using Pydantic
- 🎨 Interactive frontend for timetable visualization
- 🔄 Modular backend architecture

---

## 🛠 Tech Stack

### Backend
- Python
- FastAPI
- Pydantic

### Frontend
- HTML
- CSS
- JavaScript

### Algorithms & Data Structures
- Greedy Algorithm
- Backtracking
- Graph
- HashMap
- Set
- Priority Queue

---

## 📂 Project Structure

```
Timetable-Generator/
│
├── client/                 # Frontend
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/                 # Backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
│
├── requirements.txt
├── README.md
└── package.json
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/soyamrajkathait/sem4daa.git
cd sem4daa
```

### Install frontend dependencies

```bash
cd client
npm install
```

### Install backend dependencies

```bash
cd ../server
npm install
```

### Install Python dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

### Start Backend

```bash
cd server
npm start
```

### Start Frontend

```bash
cd client
npm run dev
```

---

## 🧠 Algorithm Overview

The scheduling engine uses a hybrid approach:

- **Greedy Algorithm** for efficient lecture allocation
- **Backtracking** to resolve scheduling conflicts
- **Graph-based conflict detection** for teachers, rooms, and sections
- **Priority Queue** for optimized scheduling order
- **HashMaps & Sets** for constant-time conflict checking

---

## 📌 REST API

Example endpoints:

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | `/api/timetable` | Fetch timetable |
| POST | `/api/timetable/generate` | Generate timetable |
| GET | `/api/teachers` | Get teachers |
| GET | `/api/rooms` | Get classrooms |

---

## 🎯 Future Enhancements

- Authentication & Role-Based Access
- PDF Timetable Export
- Excel Export
- Drag-and-Drop Timetable Editing
- Teacher Availability Preferences
- Email Notifications
- AI-based Schedule Optimization

---

## 📸 Screenshots

> Add screenshots of your application here.

---

## 👨‍💻 Author

**Soyam Raj Kathait**

- GitHub: https://github.com/soyamrajkathait

---

## ⭐ If you found this project useful, consider giving it a star!
