# 🧠 CogniFlow AI — Analytics Dashboard

> **Enterprise Intelligence Simulator, Decision Engine Monitor, and AI-Powered Rule Generation Platform**

<div align="center">

### 🚀 Autonomous Enterprise Decision Intelligence Platform

[![Live Demo](https://img.shields.io/badge/🚀%20Live%20Demo-Visit%20Platform-blue?style=for-the-badge)](https://cogniflow-ai-analytics-dashboard.vercel.app/)

### 🌐 Live Application

**https://cogniflow-ai-analytics-dashboard.vercel.app/**

*Transforming business policies into intelligent, explainable, and automated decisions.*

</div>

---

## 🌟 Overview

CogniFlow AI is an enterprise-grade decision intelligence platform that enables organizations to create, manage, simulate, explain, and optimize business decisions using AI-powered policy intelligence.

Modern enterprises rely on thousands of constantly evolving business rules across banking, insurance, healthcare, retail, logistics, and government systems. These rules are often hardcoded, difficult to maintain, and nearly impossible to audit at scale.

CogniFlow AI transforms static business policies into intelligent, explainable, and automated decision workflows through a unified enterprise dashboard.

### 🎯 Vision

> **Transform Policies into Intelligent, Explainable, and Self-Improving Enterprise Decisions**

---

## 🚀 Live Demo

### Production Deployment

👉 **https://cogniflow-ai-analytics-dashboard.vercel.app/**

Experience:

* 🤖 AI-Powered RuleGPT Builder
* 📊 Enterprise Analytics Dashboard
* 🛡️ Compliance Monitoring
* 🧪 Simulation Lab
* 🔍 Explainability Engine
* 🤝 Enterprise Copilot
* ⚡ Decision Intelligence Workflows

---

## 🖥️ Screenshots

### Dashboard Overview

![Dashboard Overview](assets/screenshots/dashboard.png)

> Real-time metrics, decision volume charts, and model performance at a glance.

### RuleGPT Builder

![RuleGPT Builder](assets/screenshots/rulegpt.png)

> Create and deploy business rules using natural language — powered by AI.

### System Architecture

![Architecture Diagram](assets/screenshots/architecture.png)

> Full-stack architecture: React frontend → FastAPI backend → AI/LLM layer + databases.

---

## 🎯 Problem We Solve

Organizations struggle with:

❌ Hardcoded business rules

❌ Slow policy deployment cycles

❌ Compliance risks

❌ Lack of explainability

❌ Fragmented decision systems

❌ Limited visibility into business decisions

### CogniFlow AI solves this by providing:

✅ Centralized Rule Management

✅ AI-Powered Policy Generation

✅ Real-Time Decision Intelligence

✅ Enterprise Compliance Monitoring

✅ Explainable AI Decisions

✅ Simulation-Based Policy Testing

---

## ✨ Features

| Module                        | Description                                                       |
| ----------------------------- | ----------------------------------------------------------------- |
| 📊 **Dashboard**              | Real-time overview of decision engine health, metrics, and alerts |
| 📝 **Rule Builder (RuleGPT)** | AI-powered natural language rule creation and management          |
| 🔍 **Explainability**         | Visualise and understand how decisions are made                   |
| 🧪 **Simulation Lab**         | Test rules and models against historical or synthetic data        |
| ⏪ **Time Machine**            | Replay past decision states and compare outcomes                  |
| 👁️ **Shadow Reviewer**       | Run shadow models in parallel for comparison                      |
| 🛡️ **Compliance Audit**      | Automated compliance checks and audit trail generation            |
| 📈 **Drift Monitor**          | Detect model and data drift in production                         |
| ⚙️ **Optimisation**           | Rule and model performance optimisation suggestions               |
| 🕸️ **Graph Memory**          | Persistent graph-based memory for agent context                   |
| 📋 **Audit Logs**             | Full history of all decisions and system events                   |
| 🤖 **AI Copilot**             | Collaborative assistant embedded across all modules               |

---

## 🏗️ Tech Stack

### Frontend

* **React 19** + **TypeScript**
* **Vite**
* **TailwindCSS v4**
* **Lucide React**
* **Motion**
* **XYFlow (React Flow)**
* **React Markdown**

### Backend

* **FastAPI**
* **SQLAlchemy**
* **LangGraph + LangChain**
* **Celery + Redis**
* **Neo4j**
* **Google Gemini API / Groq**

---

## 🏛️ Enterprise Architecture

```text
Business Users
        │
        ▼

 ┌─────────────────────┐
 │ Enterprise Copilot  │
 └──────────┬──────────┘
            │

 ┌──────────┼──────────┐
 ▼          ▼          ▼

RuleGPT  Compliance  Explainability
 Agent      Agent        Agent

 └──────────┬──────────┘
            ▼

  Decision Intelligence Core

            ▼

     Rules Engine

            ▼

PostgreSQL + Neo4j + Redis

            ▼

 Enterprise Applications
```

---

## 🚀 Getting Started

### Prerequisites

* **Node.js** v18+
* **Python** 3.10+
* **Redis** (for background tasks)
* **Neo4j** (for graph memory, optional)

---

### 1. Clone the Repository

```bash
git clone https://github.com/Rishabhv16/cogniflow-ai-analytics-dashboard.git
cd cogniflow-ai-analytics-dashboard
```

---

### 2. Frontend Setup

```bash
npm install

cp .env.example .env

npm run dev
```

Frontend runs at:

```text
http://localhost:5173
```

---

### 3. Backend Setup

```bash
cd backend

python -m venv venv

# Windows
venv\Scripts\activate

# macOS/Linux
source venv/bin/activate

pip install -r requirements.txt

cp .env.example .env

uvicorn main:app --reload --port 8000
```

Backend API runs at:

```text
http://localhost:8000
```

---

### 4. Environment Variables

```env
# Root .env

GEMINI_API_KEY=your_gemini_api_key
GROQ_API_KEY=your_groq_api_key

# backend/.env

DATABASE_URL=sqlite:///./cogniflow.db

NEO4J_URI=bolt://localhost:7687
NEO4J_USER=neo4j
NEO4J_PASSWORD=your_password

REDIS_URL=redis://localhost:6379

GEMINI_API_KEY=your_gemini_api_key
```

---

## 🐳 Docker (Optional)

Run the full stack using Docker:

```bash
docker-compose up --build
```

---

## 📁 Project Structure

```text
cogniflow-ai-analytics-dashboard/
├── src/
│   ├── components/
│   ├── App.tsx
│   ├── types.ts
│   └── index.css
│
├── backend/
│   ├── main.py
│   ├── requirements.txt
│   ├── core/
│   └── modules/
│       ├── analytics/
│       ├── compliance/
│       ├── copilot/
│       ├── explainability/
│       ├── rulegpt/
│       ├── rules_engine/
│       ├── simulation/
│       └── other_agents/
│
├── assets/
│   └── screenshots/
│
├── docker-compose.yml
├── vite.config.ts
└── package.json
```

---

## 🎯 Target Industries

🏦 Banking

🛡️ Insurance

🏥 Healthcare

🛒 Retail

🚚 Logistics

🏛️ Government

🏢 Enterprise SaaS

---

## 🏆 Built For

* AI Agents Hackathon 2026
* Adaptive Data Challenge
* Enterprise AI Innovation Programs
* Intelligent Decision Systems
* AI Governance & Compliance Platforms

---

## 📈 Roadmap

### Phase 1

* Authentication
* Rule Management
* Decision Engine

### Phase 2

* RuleGPT
* Simulation Lab

### Phase 3

* Compliance Intelligence
* Enterprise Copilot

### Phase 4

* Autonomous Decision Optimization

### Phase 5

* Enterprise Decision Operating System

---

## 📜 License

This project is private. All rights reserved.

---

## ⭐ Support

If you found this project interesting, consider giving it a star and sharing feedback.

---

<div align="center">

### 🧠 CogniFlow AI

**Autonomous Enterprise Decision Intelligence Platform**

*Transforming Business Policies into Intelligent Enterprise Decisions*

🌐 https://cogniflow-ai-analytics-dashboard.vercel.app/

</div>
