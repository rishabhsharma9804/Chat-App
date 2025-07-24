<h1 align="center">💬 Real-Time Chat App using Spring Boot & React.js</h1>

<p align="center">
  A full-stack group chat application built with <strong>Spring Boot</strong> and <strong>React.js</strong>, allowing users to create or join chat rooms using unique group IDs for seamless real-time communication.
</p>

---

## 🚀 Overview

This project is a real-time **group chat platform** where:

- Users can **create or join chat rooms** using unique group IDs.
- Messages are delivered **instantly** using WebSockets.
- The app features a **React.js frontend** and a **Spring Boot backend**, connected via REST APIs and WebSocket communication.

> 📅 Project Completion: **December 2024**

---

## ✨ Key Features

### 🧑‍🤝‍🧑 Chat Rooms
- Create or join chat rooms via unique group IDs
- View messages in real-time with auto-scroll
- Support for multiple users in a single room

### ⚙️ Backend (Spring Boot)
- REST APIs for user and room management
- WebSocket-based message broadcasting
- Robust room/session handling
- In-memory storage (or optional DB support)

### 💻 Frontend (React.js)
- Dynamic UI for room creation and chat interface
- Real-time message display with socket communication
- Responsive layout for desktop & mobile

---

## 🛠️ Tech Stack

| Tech           | Purpose                    |
|----------------|----------------------------|
| **Spring Boot**| Backend server, REST APIs, WebSocket |
| **React.js**   | Frontend interface          |
| **WebSocket**  | Real-time communication     |
| **Maven**      | Dependency management       |
| **Axios**      | HTTP API requests (frontend)|
| **Socket.io / Stomp.js** | WebSocket communication client |
| **Postman**    | API testing (optional)      |

---

## 📂 Folder Structure

```bash
chat-app/
├── backend/                  # Spring Boot project
│   ├── src/main/java/com/... # Controllers, Services, Configs
│   ├── WebSocketConfig.java  # WebSocket setup
│   ├── ChatController.java   # REST & WebSocket endpoints
│   └── pom.xml               # Maven config
│
├── frontend/                 # React app
│   ├── public/
│   ├── src/
│   │   ├── components/       # ChatRoom, JoinRoom, etc.
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
│
└── README.md

```

## 🧪 How to Run the Project
⚙️ Backend (Spring Boot)
Navigate to the backend directory:
cd backend

Build and run the Spring Boot server:
mvn spring-boot:run

Server will run on: http://localhost:8080

💻 Frontend (React.js)
Navigate to the frontend directory:
cd frontend

Install dependencies:
npm install

Start the React development server:
npm start

App will open on: http://localhost:3000

## 💡 Future Enhancements
🛡️ User authentication with JWT

💬 Message persistence in a database

🖼️ Media sharing support (images, files)

📱 Progressive Web App (PWA) support

👨‍💼 Admin/moderator features

## 📸 Screenshots
You can include screenshots of your chat UI, room join screen, and message flow here.

## 🧑‍💻 Author

**Rishabh Sharma**  
📧 rishabhsharma9804@gmail.com  
🌐 [GitHub](https://github.com/rishabhsharma9804) | [LinkedIn](https://www.linkedin.com/in/rishabhsharma9804/)

📄 License
This project is licensed under the MIT License

## 🙌 Acknowledgements
Spring Boot WebSocket reference

React + WebSocket tutorials (freeCodeCamp, Baeldung)

Socket design inspiration from Discord and Slack