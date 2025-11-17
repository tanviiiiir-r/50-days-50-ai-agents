# 💼 AI Recruitment Agent Team

A multi-agent AI-powered recruitment system that automates resume screening, candidate communication, technical evaluations, and interview scheduling — delivering a seamless, end-to-end hiring workflow.

---

## 💡 Problem

Recruiters lose countless hours manually reviewing resumes, writing emails, coordinating interviews, and assessing candidates. The hiring process is:

* Time-consuming
* Repetitive
* Error-prone
* Difficult to scale

Growing teams need an automated, intelligent system that handles repetitive tasks while improving consistency and candidate experience.

---

## 🚀 Solution

The **AI Recruitment Agent Team** brings together a coordinated set of recruitment-focused AI agents that replicate the roles of a full hiring team. Using Streamlit, Zoom API, email automation, and advanced language models, it:

* Analyzes resumes with precision
* Evaluates technical skills
* Drafts professional communication
* Coordinates interview schedules via Zoom
* Provides structured recruiter insights

This system drastically reduces recruiter workload while improving decision quality and candidate communication.

---

## ⚙️ Features

### 🤖 Specialized AI Agents

* **Technical Recruiter Agent** — Evaluates resumes, extracts skills, analyzes experience, performs technical screening
* **Communication Agent** — Generates emails, sends notifications, manages candidate responses
* **Scheduling Coordinator Agent** — Handles interview scheduling, timezone conversion, Zoom meeting creation, reminders

### 🔄 End-to-End Recruitment Workflow

* Automated resume screening
* Role-specific technical evaluations
* Smart candidate selection suggestions
* Professional email communication
* Automated Zoom interview setup
* Integrated feedback and follow-up system

### 📥 Candidate Experience

* Simple file upload interface
* Real-time updates
* Automatic reminders
* Transparent communication

---

## 🧠 Tech Stack

* **Framework:** Phidata
* **Language Model:** OpenAI GPT-4o
* **Integrations:** Zoom API, Phidata EmailTools
* **PDF Parsing:** PyPDF2
* **Frontend:** Streamlit
* **Timezone Management:** pytz
* **State Management:** Streamlit Session State

---

## 🧩 Setup Instructions

### ✔️ Requirements

You will need:

* A **dedicated Gmail account** for the recruiter
* **Google App Password** (generated via 2FA)
* **Zoom API credentials:** Account ID, Client ID, Client Secret
* **OpenAI API Key** for GPT-4o access
* Python 3.10+ installed

### 📥 Installation

Clone the official repository:

```bash
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day27_AI_Recruitment_Agent_Team

Install dependencies:

```bash
pip install -r requirements.txt
```

### 🔐 Configure Credentials

**1. Gmail App Password**

* Enable 2-Step Verification
* Generate an App Password from Google
* Copy the 16-character code (no spaces)

**2. Zoom API (Server-to-Server OAuth)**

* Go to Zoom Marketplace
* Create a new S2S OAuth app
* Retrieve:

  * Client ID
  * Client Secret
  * Account ID
* Add required scopes (list included in original description)

**3. OpenAI Key**
Add all credentials inside the Streamlit app sidebar.

### ▶️ Run the Application

```bash
streamlit run ai_recruitment_agent_team.py
```

---

## 🧭 Real-World Use Cases

* **HR Teams Automating Early Screening** → Reduce resume review time by 80%
* **Tech Companies** → Perform consistent technical skill evaluations
* **Recruitment Agencies** → Handle multiple clients with automated communication
* **Startups** → Scale hiring without hiring large HR teams
* **Global Teams** → Automated timezone-aware scheduling with Zoom

---

## 📁 Repository Info

* **Project Name:** AI Recruitment Agent Team
* **Day Number:** XX
* **Series:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack:** Streamlit, Phidata, OpenAI GPT-4o, Zoom API, PyPDF2, Python
* **License:** MIT

---

Transform your hiring workflow with a fully automated AI recruitment team — faster, smarter, and more consistent than traditional methods.
