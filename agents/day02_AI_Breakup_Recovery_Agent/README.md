# 💔 AI Breakup Recovery Agent (Day 02) 💡

## Problem Section 💡

Breakups can be emotionally challenging, leaving individuals struggling to process their feelings and find closure. Many lack immediate access to support or constructive guidance, resulting in prolonged emotional distress. An AI-powered solution can provide personalized, timely assistance to help users navigate post-breakup emotions effectively.

## Solution Section 🚀

The AI Breakup Recovery Agent uses a team of specialized AI agents to assist users in emotional recovery. By analyzing user input and optional chat screenshots, the system delivers empathetic guidance, routine planning, cathartic message generation, and honest feedback, offering a structured and supportive path to healing.

## Features ⚙️

* 🧠 **Multi-Agent Team:**

  * **Therapist Agent:** Offers empathetic support and coping strategies.
  * **Closure Agent:** Generates unsent emotional messages for catharsis.
  * **Routine Planner Agent:** Suggests daily routines to aid emotional recovery.
  * **Brutal Honesty Agent:** Provides direct, no-nonsense feedback on the breakup.
* 📷 **Chat Screenshot Analysis:** Users can upload screenshots for analysis.
* 🔑 **API Key Management:** Securely store and manage Gemini API keys.
* ⚡ **Parallel Execution:** Agents process inputs collaboratively for comprehensive insights.
* ✅ **User-Friendly Interface:** Simple and intuitive Streamlit interface.

## Tech Stack 🧠

* **Frontend:** Streamlit (Python)
* **AI Models:** Gemini 2.0 Flash (Google Vision Model)
* **Image Processing:** PIL
* **Text Extraction:** Gemini Vision model
* **Environment Variables:** Managed via `st.session_state` in Streamlit

## Setup Instructions 🧩

### Requirements

* Python 3.10 or higher
* Gemini API Key

### Installation

```bash
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day02_AI_Breakup_Recovery_Agent
pip install -r requirements.txt
```

### Run Instructions

```bash
streamlit run ai_breakup_recovery_agent.py
```

## Real-World Use Cases 🧭

* Helping users navigate emotional distress after a breakup.
* Providing daily structured routines to aid mental wellness.
* Offering cathartic messaging to release unexpressed feelings.
* Delivering honest insights to promote self-reflection and growth.

## Repository Info 📁

* **Project Name:** AI Breakup Recovery Agent
* **Day Number:** 02
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r/50-days-50-ai-agents/tree/main/agents/)
* **Tech Stack:** Streamlit, Gemini 2.0 Flash, Python, PIL
* **License:** MIT
