# Personal Productivity Dashboard

A full-stack productivity dashboard that helps users manage **notes, todos, reminders, bookmarks, quotes, text tools, and a Pomodoro timer** — all in one place.  
Built with **React + Tailwind CSS (Frontend)** and **Express.js (Backend)**, fully containerized with **Docker Compose** for easy deployment.

---

## 🚀 Features

### 📝 Notes Manager
- Create, edit, delete notes  
- Categorization + tag search  
- API-powered full CRUD support  

### ✅ To-Do Manager
- Add tasks with priority  
- Update status (pending/completed)  
- Filter by priority, status, or ID  

### ⏰ Reminders System
- Create reminders with date/time  
- Snooze, fetch today’s and upcoming reminders  

### 🔖 Bookmarks Manager
- Save useful URLs with tags and categories  
- Search and advanced filtering  

### 💬 Quotes Module
- Random quotes  
- Browse by category  
- Add or delete quotes  

### 🔧 Text Utilities
- Word count  
- Case conversions  
- Remove duplicates  
- Sort lines  
- Find & replace  

### ⏳ Pomodoro Timer
- Start/stop focus sessions  
- Track active timers  

### 📊 Dashboard Overview
- Quick summaries of all modules  
- Auto-refreshed statistics  

---

## 🛠️ Tech Stack

### **Frontend**
- React + Vite
- Tailwind CSS
- React Router
- Custom animations, glass UI, interactive cards

### **Backend**
- Express.js :contentReference[oaicite:0]{index=0}
- UUID for ID generation
- In-memory structured data store  
- 30+ REST API endpoints

### **DevOps**
- Docker  
- Docker Compose  
- Hot Reload (Frontend & Backend)

---

## 📁 Project Structure

personal-productivity-dashboard/
│── backend/
│ ├── index.js
│ ├── package.json
│ └── Dockerfile
│
│── frontend/
│ ├── src/
│ │ ├── App.jsx
│ │ ├── main.jsx
│ │ ├── index.css
│ │ ├── config.js
│ │ └── components/
│ ├── package.json
│ ├── index.html
│ └── Dockerfile
│
│── docker-compose.yml
│── README.md


---

## ▶️ Running With Docker

### **1. Start everything**
docker-compose up --build

2. Access services

Frontend → http://localhost:3000

Backend API → http://localhost:4000/api

Health Check → http://localhost:4000/api/health


3. Stop services
docker-compose down

