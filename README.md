# 🤖 100 AI Agents Bootcamp: From Zero to Agentic Mastery

Welcome to the **100 AI Agents Bootcamp**! This repository is a comprehensive collection of 100 specialized AI agent labs designed to take you from a beginner to an expert in building agentic systems.

Whether you're interested in Finance, HR, Marketing, or IT Operations, this bootcamp provides hands-on, step-by-step guides to implementing AI agents using modern tools like **LangChain**, **OpenAI**, and **Streamlit**.

---

## 🚀 Getting Started

Every agent in this repository follows a modular structure, making it easy to spin up a specific lab in minutes.

### 1. Prerequisites
Ensure you have Python 3.9+ installed and an OpenAI API Key.
```bash
# Clone the repository
git clone https://github.com/your-repo/AI-agents-bootcamp.git
cd AI-agents-bootcamp
```

### 2. Universal Setup
For any agent lab (e.g., Agent #1), follow these steps:
```bash
# 1. Create a directory for your work (optional, but recommended in the labs)
# 2. Set up a virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 3. Install core dependencies
pip install openai langchain streamlit pandas
```

### 3. Run an Agent
Each lab includes an `app.py` or similar entry point. Start the UI using:
```bash
export OPENAI_API_KEY='your-key-here'
streamlit run app.py
```

---

## 🧩 Anatomy of an Agent Lab

Every lab file (e.g., `Agent #1.md`) is meticulously structured to ensure a consistent learning experience. Here is what each agent lab composes of:

1.  🧠 **Overview**: A high-level explanation of the agent's purpose, the problem it solves, and the business value it provides.
2.  🧪 **Lab Objectives**: Clear, bulleted goals of what you will build and learn during the lab.
3.  🧰 **Tech Stack**: The specific library requirements (e.g., LangChain, Pandas, GPT-4) needed for that specific agent.
4.  🧭 **Step-by-Step Instructions**:
    *   **Environment Setup**: Specific pip installs or directory structures.
    *   **Data Simulation**: Mocking the necessary data (resumes, financial logs, etc.).
    *   **Prompt Engineering**: Defining the `PromptTemplate` that gives the agent its "personality" and logic.
    *   **Agent Logic**: The Python core using LangChain to connect the LLM to logic.
    *   **UI Implementation**: Building a functional dashboard or chat interface using Streamlit.
5.  🧪 **Example Output**: A preview of what to expect when the agent runs successfully, including sample logs or UI screenshots.

---

## 📂 The 100 Agents Directory

The agents are organized into 10 domain-specific clusters. click the links below to dive into any lab!

### 💰 Finance & Accounting (#1 - #10)
*   [#1: Individualized Financial Advisory Agent](file:///e:/agents/AI-agents-bootcamp/Agent%20#1%20Individualized%20Financial%20Advisory%20Agent.md)
*   [#2: Ledger Agent](file:///e:/agents/AI-agents-bootcamp/Agent%20#2%20Ledger%20Agent.md)
*   [#10: AI Portfolio Manager](file:///e:/agents/AI-agents-bootcamp/Agent%20#10%20AI%20Portfolio%20Manager.md)
*   *(And More: Prediction, Fraud Detection, Invoicing, Tax Compliance...)*

### 👔 Human Resources (#11 - #20)
*   [#11: Employee Hiring Advisor](file:///e:/agents/AI-agents-bootcamp/Agent%20#11%20Employee%20Hiring%20Advisor.md)
*   [#15: AI Recruitment Coordinator](file:///e:/agents/AI-agents-bootcamp/Agent%20#15%20AI%20Recruitment%20Coordinator.md)
*   [#19: Performance Review Agent](file:///e:/agents/AI-agents-bootcamp/Agent%20#19%20Performance%20Review%20Agent.md)

### 📦 Procurement & Supply Chain (#21 - #30)
*   [#21: Supplier Risk Assessment Agent](file:///e:/agents/AI-agents-bootcamp/Agent%20#21%20Supplier%20Risk%20Assessment%20Agent.md)
*   [#25: AI-driven Negotiation Agent](file:///e:/agents/AI-agents-bootcamp/Agent%20#25%20AI-driven%20Negotiation%20Agent.md)

### 📈 Sales Intelligence (#31 - #40)
*   [#31: Lead Scoring Agent](file:///e:/agents/AI-agents-bootcamp/Agent%20#31%20Lead%20Scoring%20Agent.md)
*   [#35: Automated Proposal Generator](file:///e:/agents/AI-agents-bootcamp/Agent%20#35%20Automated%20Proposal%20Generator.md)

### 📣 Marketing & Content (#41 - #50)
*   [#41: Content Generation Agent](file:///e:/agents/AI-agents-bootcamp/Agent%20#41%20Content%20Generation%20Agent.md)
*   [#48: Personalized Email Marketing Agent](file:///e:/agents/AI-agents-bootcamp/Agent%20#48%20Personalized%20Email%20Marketing%20Agent.md)

### 💻 IT, Security & DevOps (#51 - #60)
*   [#52: Security Threat Detection Agent](file:///e:/agents/AI-agents-bootcamp/Agent%20#52%20Security%20Threat%20Detection%20Agent.md)
*   [#57: AI Code Review Agent](file:///e:/agents/AI-agents-bootcamp/Agent%20#57%20AI%20Code%20Review%20Agent.md)

### 🎧 Customer Experience & Ops (#61 - #70)
*   [#61: AI Chatbot for Customer Support](file:///e:/agents/AI-agents-bootcamp/Agent%20#61%20AI%20Chatbot%20for%20Customer%20Support.md)
*   [#67: AI-powered Virtual Assistant](file:///e:/agents/AI-agents-bootcamp/Agent%20#67%20AI-powered%20Virtual%20Assistant.md)

### 🏭 Operations & Logistics (#71 - #80)
*   [#71: Predictive Maintenance Agent](file:///e:/agents/AI-agents-bootcamp/Agent%20#71%20Predictive%20Maintenance%20Agent.md)
*   [#76: AI-powered Logistics Routing Agent](file:///e:/agents/AI-agents-bootcamp/Agent%20#76%20AI-powered%20Logistics%20Routing%20Agent.md)

### ⚖️ Legal, Risk & Compliance (#81 - #90)
*   [#81: Contract Review Agent](file:///e:/agents/AI-agents-bootcamp/Agent%20#81%20Contract%20Review%20Agent.md)
*   [#86: Data Privacy Compliance Agent](file:///e:/agents/AI-agents-bootcamp/Agent%20#86%20Data%20Privacy%20Compliance%20Agent.md)

### 🏆 Strategy & Executive Support (#91 - #100)
*   [#91: AI Meeting Notes Agent](file:///e:/agents/AI-agents-bootcamp/Agent%20#91%20AI%20Meeting%20Notes%20Agent.md)
*   [#97: Business Strategy Advisor](file:///e:/agents/AI-agents-bootcamp/Agent%20#97%20Business%20Strategy%20Advisor.md)
*   [#100: Executive Summary Generator Agent](file:///e:/agents/AI-agents-bootcamp/Agent%20#100%20Executive%20Summary%20Generator%20Agent.md)

---

## 🛠 Unified Tech Stack

While each lab is unique, the core foundation remains consistent across the bootcamp:

*   **Language**: Python 3.9+
*   **Orchestration**: [LangChain](https://www.langchain.com/) (Chains, Prompts, Output Parsers)
*   **Intelligence**: OpenAI GPT-4o / GPT-4-turbo
*   **Interfaces**: [Streamlit](https://streamlit.io/) (for rapid AI prototyping)
*   **Data**: Pandas & NumPy for numerical/mock analysis

---

## ⚖️ License

Distributed under the MIT License. See `LICENSE` for more information.