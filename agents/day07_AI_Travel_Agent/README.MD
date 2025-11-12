# 🛫 AI Travel Agent (Day 07) 💡

## Problem Section 💡

Planning a trip involves researching destinations, activities, accommodations, and organizing schedules, which can be time-consuming and overwhelming. Many travelers struggle to create personalized itineraries without spending hours on the internet. There is a need for an AI solution to simplify travel planning and generate ready-to-use itineraries efficiently.

## Solution Section 🚀

The AI Travel Agent uses GPT-4o to generate intelligent, personalized travel itineraries. By combining web research via SerpAPI and AI planning, the system produces detailed daily schedules, suggests activities, dining, and accommodations, and allows users to download their itinerary as a calendar file. A local version using Ollama ensures privacy and offline usage.

## Features ⚙️

* Research and discover travel destinations, activities, and accommodations.
* Customize itineraries based on travel duration.
* Generate intelligent, personalized plans using GPT-4o.
* Download itineraries as .ics calendar files for Google, Apple, or other calendars.
* Local LLM support with Ollama for offline inference.

## Tech Stack 🧠

* **Frontend:** Streamlit (Python)
* **AI Models:** GPT-4o, Ollama (local)
* **Web Research:** SerpAPI
* **Calendar Integration:** .ics file generation
* **Environment Management:** API keys via Streamlit sidebar

## Setup Instructions 🧩

### Requirements

* Python 3.10 or higher
* OpenAI API Key (for cloud version)
* SerpAPI Key (for web research)
* Ollama installation (for local version, optional)

### Installation

```bash
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day07_AI_Travel_Agent
pip install -r requirements.txt
```

### Run Instructions

**Cloud Version (OpenAI GPT-4o):**

```bash
streamlit run travel_agent.py
```

**Local Version (Ollama):**

```bash
streamlit run local_travel_agent.py
```

## How It Works

* **Researcher:** Generates search queries based on user input and retrieves relevant travel info using SerpAPI.
* **Planner:** Uses AI to create detailed daily itineraries including activities, dining, and accommodations.
* Calendar download allows importing the itinerary as an all-day event schedule in your preferred calendar app.

## Real-World Use Cases 🧭

* Automate trip planning for vacations, business trips, or family travel.
* Quickly generate ready-to-use, personalized travel schedules.
* Integrate itineraries with calendars for easy tracking.
* Enable offline travel planning with local LLM inference.

## Repository Info 📁

* **Project Name:** AI Travel Agent
* **Day Number:** 07
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r/)
* **Tech Stack:** Streamlit, GPT-4o, Ollama, SerpAPI, Python
* **License:** MIT
