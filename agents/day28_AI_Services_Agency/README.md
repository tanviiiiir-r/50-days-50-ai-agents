# 🧠 AI Services Agency

## 💡 Problem

Building software is complex. Startups often need strategic guidance, technical architecture, product planning, development direction, and go‑to‑market support — all at once. But hiring a full team is expensive and slow.

## 🚀 Solution

The **AI Services Agency** simulates a complete digital agency using multiple specialized AI agents. Each agent plays a real-world role — CEO, CTO, Product Manager, Developer, and Client Success — collaborating asynchronously to analyze your startup idea and generate a complete, end‑to‑end project plan.

This system acts like an on‑demand agency that can:

* Evaluate your startup idea
* Generate technical architecture & feasibility analysis
* Create a product roadmap
* Estimate development timelines & costs
* Plan marketing & go‑to‑market strategy
* Provide coordinated, multi-agent recommendations

A full agency — but fully automated.

---

## 🏗️ Multi‑Agent Team

### 👨‍💼 CEO Agent — *Strategic Leader*

* Evaluates startup potential using structured frameworks
* Makes final product, tech, financial, and marketing decisions
* Uses **AnalyzeStartupTool** & **MakeStrategicDecision**

### 🛠️ CTO Agent — *Technical Architect*

* Analyzes technical requirements
* Designs architecture & core components
* Uses **QueryTechnicalRequirements** & **EvaluateTechnicalFeasibility**

### 🧭 Product Manager Agent — *Product Strategist*

* Creates product strategy & roadmap
* Defines MVP and feature progression
* Bridges between technical & marketing teams

### 👨‍💻 Developer Agent — *Implementation Expert*

* Suggests tech stack, frameworks, APIs, and cloud setup
* Creates implementation-level detail
* Generates cost & timeline estimates

### 📣 Client Success Agent — *Marketing & Growth Lead*

* Designs go-to-market strategies
* Maps customer acquisition channels
* Works with PM on feature–market alignment

---

## 🛠️ Custom Tools

The AI Services Agency uses OpenAI Schema tools for structured reasoning:

### 🔍 **Analysis Tools**

* `AnalyzeProjectRequirements` — Market, competitors, risks
* `AnalyzeStartupIdea` — Opportunity score, business viability

### ⚙️ **Technical Tools**

* `CreateTechnicalSpecification` — Architecture, data models, integrations

These tools allow agents to share structured outputs instead of plain text.

---

## 🔄 Asynchronous Multi-Agent Collaboration

The system runs all agents **in parallel** using async mode:

* Faster responses
* Real-time agent discussions
* Efficient collaboration
* Non‑blocking tool usage

### 🔗 Agent Communication Map

* **CEO ↔️ All agents** (oversight)
* **CTO ↔️ Developer** (technical planning)
* **PM ↔️ Marketing** (GTM strategy)
* **PM ↔️ Developer** (feature implementation)

---

## ▶️ Demo

https: //github.com/user-attachments/assets/a0befa3a-f4c3-400d-9790-4b9e37254405

---

## 🧪 How to Run

### 1️⃣ Clone the Repo

```bash
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/dayXX_Ai_Services_Agency
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit App

```bash
streamlit run agency.py
```

### 4️⃣ Enter Your OpenAI API Key

Get your key here:
https: //platform.openai.com/api-keys

Then paste it into the sidebar — your personal AI agency will start evaluating your startup idea immediately.

---

Want this transformed into a **complete GitHub project**, **video demo script**, or **architecture diagram**? I can add them instantly.
