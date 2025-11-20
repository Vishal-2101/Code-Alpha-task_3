# ✔️ TeamTask — Collaborative Project Management Platform

A lightweight, team-oriented task management system inspired by Trello and Asana — built with a scalable architecture, real-time communication capabilities, and modern UI principles.

# 🌐 Live Deployment

🔗 https://teamtask.zite.so/

(Current development build — features rolling out continuously)

# 📌 Project Overview

TeamTask is an evolving collaborative project management system designed to simplify teamwork through intuitive project boards and task-level communication.
The system is engineered with extensibility, real-time responsiveness, and clean modularity in mind.

This repository tracks the early build cycle, including core infrastructure, backend entities, and UI/UX composition.

# ✨ Core Functionalities
✔ Implemented / Under Development

Create and manage group projects

Assign tasks to specific team members

Comment within tasks for contextual communication

User authentication system (JWT + protected routing)

Modular project boards

Dynamic task cards

# 🚀 Planned Enhancements

WebSockets for real-time updates (task changes, new comments, notifications)

Activity Feed + event tracking

Drag-and-drop task management

Role-based permissions

Team invitations & membership management

# 🧠 Architectural Overview
System Model
Users ─┬── Projects ─┬── Tasks ─┬── Comments
       │              │          └── Attachments (future)
       │              └── Task Groups (future)
       └── Notifications (WebSocket-based)

Backend Layer

REST API

Entity-driven structure (User, Project, Task, Comment)

Clean separation: controllers → services → models

Frontend Layer

Component-driven layout

Board → Column → Card hierarchical UI

State management for multi-project workflows

# 🛠️ Tech Stack
Frontend

React / Next.js

Tailwind CSS

Context API / Redux (depending on your implementation)

Backend

Node.js

Express.js

MongoDB (Mongoose ORM)

Real-Time Layer (Upcoming)

WebSockets / Socket.io

Utilities

JWT Authentication

REST API

Zite Hosting

# 🖼️ Screenshot (Uploaded)

Project Dashboard:
<img width="1919" height="838" alt="image" src="https://github.com/user-attachments/assets/7e6fcc15-b35e-433b-b2dc-0e7735e7a66e" />

Task Dashboard:
<img width="1918" height="822" alt="image" src="https://github.com/user-attachments/assets/7709014b-4733-43ff-aac2-9964235f6185" />

# 📥 Installation & Setup:

# Clone the repository
git clone https://github.com/your-username/teamtask.git

cd teamtask

# Install dependencies
npm install

# Start development server
npm run dev

# 📁 Suggested Folder Structure
teamtask/
│── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── services/
│
│── frontend/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── context/
│   └── styles/
│
└── README.md

# 🤝 Contributing

Contributions, issue reports, and feature suggestions are welcome.
Feel free to open a pull request and improve the system.

# ⭐ Support

If this project inspired you or helped you learn, consider leaving a star ⭐ on GitHub — it motivates future development!
