# 🤖 NAVA AI – Full Stack AI Agent Platform

A full-stack AI agent platform built using **OpenManus**, enabling users to create, execute, and interact with AI agents through a modern web interface with real-time feedback.

---

## 🚀 Overview

**NAVA AI** combines a **Python FastAPI backend** with a **React + TypeScript frontend** to provide an interactive sandbox for AI agents.  
Users can run agents, view live logs, manage generated files, and interact dynamically during agent execution.

This project was developed as part of the **AI Mini Agents Virtual Internship** under the  
**School of Artificial Intelligence, North-Chiang Mai University (NCMU), Thailand**.

---

## ✨ Features

### 🧠 AI Agent Capabilities
- Real-time agent execution with live log streaming  
- Tool-based modular agent architecture  
- Dynamic user input during agent execution  
- Support for multiple LLM providers (OpenAI, Azure, AWS Bedrock, custom models)

### 🎨 Frontend
- React 18 + TypeScript (Vite)
- Tailwind CSS for styling
- Clerk authentication
- File viewer with syntax highlighting
- Live HTML preview & image rendering
- Responsive UI with dark/light mode

### ⚙️ Backend
- FastAPI (async, high-performance)
- WebSocket-based real-time communication
- Modular agent and tool framework
- Browser automation using Playwright
- Structured logging and error handling

---

## 🏗️ Architecture

OpenManus/
├── frontend/
│ ├── components/
│ ├── public/
│ └── server/ # WebSocket proxy
│
├── backend/
│ ├── app/
│ │ ├── agent/
│ │ ├── tool/
│ │ ├── prompt/
│ ├── config/
│ ├── workspace/
│ └── api.py
│
└── README.md

---

## 🛠️ Tech Stack

**Frontend:**  
React, TypeScript, Vite, Tailwind CSS, Clerk, WebSockets

**Backend:**  
Python 3.12, FastAPI, Pydantic, Playwright, OpenAI API

---

## ⚙️ Installation

### Prerequisites
- Python 3.11+
- Node.js 18+
- Git

### Backend Setup
```bash
git clone https://github.com/your-username/nava-ai.git
cd backend
pip install -r requirements.txt
uvicorn api:app --host 0.0.0.0 --port 8000
Backend runs at: http://localhost:8000
Frontend Setup
cd frontend
npm install
npm run dev


Frontend runs at: http://localhost:5173

🎮 Usage

Sign in using Clerk authentication

Navigate to the Sandbox

Enter an AI task prompt

Observe real-time execution and logs

View generated files and previews instantly

👩‍💻 My Contribution

Contributed as a Full-Stack Developer during the internship

Worked on frontend–backend integration

Implemented UI components and API interactions

Assisted with WebSocket communication and agent execution flow

Collaborated on debugging, testing, and feature improvements

🎓 Internship Details

AI Mini Agents Virtual Internship
School of Artificial Intelligence
North-Chiang Mai University (NCMU), Thailand

📄 License

This project is licensed under the MIT License.

⭐ Acknowledgments

OpenManus Framework

FastAPI & React communities

NCMU School of Artificial Intelligence
