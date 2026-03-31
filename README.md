# 💼 Finance Team AI Agents

A lightweight multi-agent AI system that simulates a **financial analyst team** using GPT-4o.
This project demonstrates how multiple specialized AI agents can collaborate to deliver **comprehensive financial insights** using web data and financial APIs.

---

## 🚀 Overview

This project builds a team of AI agents in just ~20 lines of Python code, where each agent has a specific role:

* 🌐 **Web Agent** → Performs general internet research
* 📊 **Finance Agent** → Handles financial analysis and data processing
* 🧠 **Team Agent** → Coordinates communication between agents

Together, they provide intelligent, real-time financial insights.

---

## ✨ Features

* 🤖 Multi-agent architecture with role-based specialization
* 🌍 Web search using DuckDuckGo
* 📈 Real-time financial data via Yahoo Finance (YFinance)
* 🧾 Persistent storage using SQLite
* ⚡ Fast setup and minimal codebase
* 🖥️ Interactive playground interface

---

## 🛠️ Installation

### 1. Clone or Download the Repository

You can either:

* Clone the repository using Git
* OR download it as a ZIP and extract it

---

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Setup API Key

You need an OpenAI (or compatible LLM provider) API key.

### On macOS/Linux:

```bash
export OPENAI_API_KEY='your-api-key-here'
```

### On Windows (PowerShell):

```powershell
setx OPENAI_API_KEY "your-api-key-here"
```

---

## ▶️ Running the Project

```bash
python3 finance_agent_team.py
```

---

## 🌐 Access the Application

After running the script:

1. Check the console output
2. Open the provided URL in your browser
3. Start interacting with your AI Finance Team 🎉

---

## 🧠 How It Works

1. User sends a query
2. Team Agent analyzes the request
3. Delegates tasks to:

   * Web Agent (for external info)
   * Finance Agent (for financial insights)
4. Combines results into a final response

---

## 📦 Tech Stack

* Python 🐍
* GPT-4o (LLM)
* DuckDuckGo Search
* YFinance API
* SQLite

---

## ⚠️ Disclaimer

This project is for **educational and experimental purposes only**.
It should not be used as financial advice.

---

## 🙌 Credits

Inspired by modern **AI agent systems and collaborative intelligence frameworks**.

---

## 📌 Future Improvements

* Add frontend dashboard (React)
* Integrate vector database for memory
* Add multi-agent reasoning visualization
* Deploy on cloud (Docker + AWS/GCP)

---

## ⭐ If you like this project

Give it a star ⭐ and share it with others!
