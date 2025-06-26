# 🚀 AI-Driven Intelligent Trading Assistant

An advanced, AI-powered trading assistant built to help traders and investors make **informed**, **automated**, and **data-driven decisions** using cutting-edge machine learning, financial analytics, and intelligent automation.

---

## 🧭 Overview

This system integrates:
- 🔍 **Sentiment Analysis** from news and social media  
- 📊 **Historical Data Forecasting** using time-series models  
- ⚡ **Real-Time Market Monitoring** with technical indicators  
- 🤖 **AI Agents** that generate and act on trading signals  
- 🌐 **Modern Web UI** to interact with the AI assistant

---

## 📁 Repository Structure

The repository includes both **frontend** and **backend** logic, along with datasets, AI models, and pipeline scripts.

├── .gitattributes

├── TATAMOTORS.NS.csv # Example dataset for Tata Motors

├── app.py # Backend logic or trading prototype

├── Trade-AI/ # Main frontend + AI agent directory


---

### 📂 Trade-AI Directory

This is the core project directory containing the **TypeScript/Node.js frontend**, AI models, and logic.

#### 📄 Key Files

- `README.md` – Sub-project documentation  
- `.gitignore` – Ignore rules for the directory  
- `package.json`, `bun.lockb`, `package-lock.json` – Dependency definitions  
- `index.html` – Web application entry point  
- Config files:  
  - `eslint.config.js`, `tailwind.config.ts`, `tsconfig.json`, `vite.config.ts`, etc.  
  - For linting, styling, TypeScript support, and Vite build setup  

#### 📁 Key Folders

| Folder            | Purpose                                                                 |
|------------------|-------------------------------------------------------------------------|
| `AI Model/`       | Machine learning models for signal prediction                          |
| `Data forming/`   | Scripts for data collection, preprocessing, and feature engineering    |
| `ai_agents/`      | Autonomous agents that process signals and execute trading decisions   |
| `pipeline/`       | Data/model pipelines for training, testing, and deployment             |
| `public/`         | Static assets (icons, favicons, etc.)                                  |
| `src/`            | Frontend UI logic (components, views, services, API calls)             |
| `generated_text.txt` | Output from models or logs (e.g., GPT-generated signal descriptions)  |

---

## 🛠 Getting Started

### 🔧 Prerequisites

- Python 3.8+
- Node.js or [Bun](https://bun.sh/)
- Git
- API keys (e.g., Yahoo Finance, NewsAPI, broker APIs)

---

### 🚀 Installation

#### 1. Clone the Repository
```
git clone https://github.com/AI-Driven-Intelligent-Trading-Assistant/AI-Driven-Intelligent-Trading-Assistant.git
cd TradeScribe-AI
```
2. Install Node Dependencies
```
npm install
```

### ▶️ Run the Project

1. Start the Web UI
```
npm run dev
```
2. Run Backend Trading Logic
```
python app.py
```

## 💡 Project Highlights

| Feature                    | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| 📈 **Market Data Aggregation** | Pulls historical and live data (see `TATAMOTORS.NS.csv`)                      |
| 🧠 **AI Signal Generation**    | Uses ML models in `AI Model/` and logic in `ai_agents/`                         |
| 🤖 **Automated Trading**       | Execution logic in `app.py` and `Trade-AI/src/ai_agents/`                      |
| 🌐 **Web Interface**           | Vite + Tailwind-based UI in `Trade-AI/src`                                     |
| 🔄 **Configurable Pipelines**  | Data pipelines and preprocessing in `Data forming/` and `pipeline/`             |
| 🧪 **Backtesting & Simulations** | Support for strategy validation and performance analysis *(coming soon)*       |
