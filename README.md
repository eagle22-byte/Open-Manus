# 🤖 NAVA AI – Full Stack AI Agent Platform

A full-stack AI agent platform built using **OpenManus**, enabling users to create, execute, and interact with AI agents through a modern web interface with real-time feedback.

---

## 🚀 Overview

**NAVA AI** is an interactive AI agent system that combines a **Python FastAPI backend** with a **React + TypeScript frontend**.  
The platform provides a sandboxed environment where users can run AI agents, monitor live logs, manage generated files, and interact dynamically during agent execution.

This project was developed as part of the **AI Mini Agents Virtual Internship** under the  
**School of Artificial Intelligence, North-Chiang Mai University (NCMU), Thailand**.

---

## ✨ Features

### 🧠 AI Agent Capabilities
- Real-time agent execution with live log streaming
- Tool-based, modular agent architecture
- Dynamic user input during agent execution
- Support for multiple LLM providers (OpenAI, Azure, AWS Bedrock, custom models)

### 🎨 Frontend
- React 18 + TypeScript (Vite)
- Tailwind CSS for modern UI styling
- Clerk-based authentication
- File viewer with syntax highlighting
- Live HTML preview and image rendering
- Responsive UI with dark/light theme support

### ⚙️ Backend
- FastAPI for high-performance async APIs
- WebSocket-based real-time communication
- Modular agent and tool framework
- Browser automation using Playwright
- Structured logging and robust error handling

---

## 🏗️ Project Architecture
```bash
OpenManus/
├── frontend/          # React + TypeScript frontend
│   ├── components/    # React components
│   ├── public/        # Static assets
│   └── server/        # Node.js WebSocket proxy
│
├── backend/           # Python FastAPI backend
│   ├── app/          # Core application
│   │   ├── agent/    # Agent implementations
│   │   ├── tool/     # Tool implementations
│   │   ├── prompt/   # System prompts
│   │   └── ...
│   ├── config/       # Configuration files
│   ├── workspace/    # Agent workspace
│   └── api.py        # Main API server
│
└── README.md         # This file
```
---

## 🛠️ Tech Stack

### Frontend
- React
- TypeScript
- Vite
- Tailwind CSS
- Clerk Authentication
- WebSockets

### Backend
- Python 3.12
- FastAPI
- Pydantic
- Playwright
- OpenAI API

---

## ⚙️ Installation & Setup

### Prerequisites
- Python 3.11+
- Node.js 18+
- Git

## ⚙️ Running the Application

**Backend will run at:**  
👉 http://localhost:8000

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
**Frontend will run at:**  
👉 http://localhost:5173

---

## 🎮 Usage

- Sign in using **Clerk authentication**
- Navigate to the **Sandbox**
- Enter an AI task prompt
- Observe real-time agent execution and logs
- View generated files and previews instantly

---

## 👩‍💻 My Contribution

- Contributed as a **Full-Stack Developer** during the internship
- Worked on **frontend–backend integration**
- Implemented **UI components and API interactions**
- Assisted with **WebSocket communication** and agent execution flow
- Collaborated on **debugging, testing, and feature enhancements**

---

## 🎓 Internship Details

**AI Mini Agents Virtual Internship**  
School of Artificial Intelligence  
**North-Chiang Mai University (NCMU), Thailand**

---

## 📄 License

This project is licensed under the **MIT License**.

---

## ⭐ Acknowledgments

- OpenManus Framework
- FastAPI & React Communities
- NCMU School of Artificial Intelligence
