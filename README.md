# Al-Powered-Attendance-Performance-Tracking-System
# 🤖 AI-Agent Powered Attendance & Performance Tracker

A **simple AI-powered project** that uses **face recognition** to mark attendance, stores performance data, and lets teachers/managers **chat with an AI agent** to get insights.

---

## ✨ Features
- **Automatic Attendance** → Face recognition using webcam.  
- **Performance Tracking** → Enter marks or task scores into system.  
- **AI Agent Q&A** → Ask questions like:
  - "Who has the lowest attendance?"
  - "Show me the top performer."
- **Dashboard** → View attendance & performance in charts.

---

## 🏗️ How It Works
1. Webcam captures face → AI model verifies → Attendance saved.  
2. Teacher/Manager enters marks (via form).  
3. AI Agent fetches answers from DB (via LangChain + LLM).  
4. Dashboard shows:
   - Attendance % (bar chart/pie chart)
   - Performance trends (line chart)

---

## 🚀 Quick Start
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/ai-attendance-tracker.git
   cd ai-attendance-tracker
Install dependencies:

pip install -r requirements.txt
npm install   # if using React dashboard


Run backend (Flask/FastAPI):

uvicorn app:app --reload


Start dashboard:

npm run dev

🧠 Tech Stack

Python (FastAPI/Flask) → Face recognition + AI agent

OpenCV + DeepFace → Face recognition

LangChain + LLaMA/GPT4All → Simple AI agent

MongoDB → Store attendance & marks

React.js / Chart.js → Dashboard (or simple HTML)

🎯 Demo Flow

Student looks at camera → attendance marked.

Teacher enters marks → stored in DB.

Ask agent → "Who has <75% attendance?" → Agent replies.

Dashboard updates with simple charts.
