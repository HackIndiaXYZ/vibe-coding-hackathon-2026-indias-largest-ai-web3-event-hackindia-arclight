# 🧠 CogniFlow AI — Analytics Dashboard

> **Enterprise intelligence simulator, decision engine monitor, and rule generator with collaborative AI Copilot.**

CogniFlow AI is a full-stack analytics dashboard that gives enterprise teams complete visibility and control over AI-driven decision systems — from rule creation and compliance audits to model explainability and drift monitoring.

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

## ✨ Features

| Module | Description |
|---|---|
| 📊 **Dashboard** | Real-time overview of decision engine health, metrics, and alerts |
| 📝 **Rule Builder (RuleGPT)** | AI-powered natural language rule creation and management |
| 🔍 **Explainability** | Visualise and understand how decisions are made |
| 🧪 **Simulation Lab** | Test rules and models against historical or synthetic data |
| ⏪ **Time Machine** | Replay past decision states and compare outcomes |
| 👁️ **Shadow Reviewer** | Run shadow models in parallel for comparison |
| 🛡️ **Compliance Audit** | Automated compliance checks and audit trail generation |
| 📈 **Drift Monitor** | Detect model and data drift in production |
| ⚙️ **Optimisation** | Rule and model performance optimisation suggestions |
| 🕸️ **Graph Memory** | Persistent graph-based memory for agent context |
| 📋 **Audit Logs** | Full history of all decisions and system events |
| 🤖 **AI Copilot** | Collaborative assistant embedded across all modules |

---

## 🏗️ Tech Stack

### Frontend
- **React 19** + **TypeScript** — UI framework
- **Vite** — Build tool and dev server
- **TailwindCSS v4** — Styling
- **Lucide React** — Icons
- **Motion** — Animations
- **XYFlow (React Flow)** — Graph visualisations
- **React Markdown** — Markdown rendering

### Backend
- **FastAPI** — REST API framework
- **SQLAlchemy** — ORM
- **LangGraph + LangChain** — AI agent orchestration
- **Celery + Redis** — Task queue
- **Neo4j** — Graph memory database
- **Google Gemini API / Groq** — LLM providers

---

## 🚀 Getting Started

### Prerequisites
- **Node.js** v18+
- **Python** 3.10+
- **Redis** (for background tasks)
- **Neo4j** (for graph memory, optional)

---

### 1. Clone the Repository

```bash
git clone https://github.com/Rishabhv16/cogniflow-ai-analytics-dashboard.git
cd cogniflow-ai-analytics-dashboard
```

---

### 2. Frontend Setup

```bash
# Install dependencies
npm install

# Copy env file and add your API keys
cp .env.example .env

# Start the dev server
npm run dev
```

The frontend will be available at `http://localhost:5173`.

---

### 3. Backend Setup

```bash
cd backend

# Create a virtual environment
python -m venv venv

# Activate it
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Copy env file and add your API keys
cp .env.example .env

# Run the FastAPI server
uvicorn main:app --reload --port 8000
```

The backend API will be available at `http://localhost:8000`.

---

### 4. Environment Variables

Create a `.env` file in the root and in `/backend` based on `.env.example`.

Key variables:

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

Run the full stack with Docker Compose:

```bash
docker-compose up --build
```

---

## 📁 Project Structure

```
cogniflow-ai-analytics-dashboard/
├── src/
│   ├── components/         # React UI components (Dashboard, RuleBuilder, etc.)
│   ├── App.tsx             # Main app with routing
│   ├── types.ts            # TypeScript type definitions
│   └── index.css           # Global styles
├── backend/
│   ├── main.py             # FastAPI app entry point
│   ├── requirements.txt    # Python dependencies
│   ├── core/               # Config, database, core utilities
│   └── modules/            # Feature modules
│       ├── analytics/      # Analytics & metrics
│       ├── compliance/     # Compliance audit agent
│       ├── copilot/        # AI Copilot
│       ├── explainability/ # Decision explainability
│       ├── rulegpt/        # RuleGPT agent
│       ├── rules_engine/   # Rule execution engine
│       ├── simulation/     # Simulation lab
│       └── other_agents/   # Additional AI agents
├── assets/
│   └── screenshots/        # README screenshots
├── docker-compose.yml
├── vite.config.ts
└── package.json
```

---

## 📜 License

This project is private. All rights reserved.

---

<div align="center">
  <p>Built with ❤️ by <a href="https://github.com/Rishabhv16">Rishabh</a></p>
</div>
