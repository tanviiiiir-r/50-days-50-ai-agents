# Self-Guided AI Audio Tour Agent 🎧🤖

## Problem 💡

Tourists and explorers often miss out on local history, architecture, culture, and cuisine because static guides are generic and do not adapt to real-time context or personal interests. Current audio tours lack personalization, dynamic pacing, and expressive storytelling, making it hard for users to enjoy immersive, self-guided experiences.

This agent exists to provide an interactive, location-aware audio tour experience that adapts to individual interests and tour durations, delivering rich narratives and high-quality speech in real-time.

## Solution 🚀

The **Self-Guided AI Audio Tour Agent** is a conversational multi-agent system built with OpenAI Agents SDK. Each specialized agent contributes content in its domain, coordinated by the Orchestrator Agent, to produce an immersive, seamless audio tour:

* **Orchestrator Agent**: Manages tour flow, transitions, and content integration from all expert agents.
* **History Agent**: Delivers engaging historical narratives.
* **Architecture Agent**: Highlights architectural details and design elements.
* **Culture Agent**: Explains local customs, traditions, and arts.
* **Culinary Agent**: Describes iconic dishes and food culture.

The system integrates real-time web searches, adapts to user location and interests, and outputs expressive audio using GPT-4o Mini Audio.

## Features ⚙️

* Multi-agent architecture with coordinated content generation
* Location-aware tour personalization
* Real-time web search for up-to-date information
* Selectable tour durations (15, 30, 60 minutes) with proportionate content pacing
* Expressive text-to-speech output via GPT-4o Mini Audio
* User-focused, immersive storytelling for history, architecture, culture, and cuisine

## Tech Stack 🧠

* Python 3.10+
* Streamlit (web interface)
* OpenAI Agents SDK
* GPT-4o Mini Audio (TTS)
* Web search integration for real-time information
* Standard Python libraries: `requests`, `dotenv`

## Setup Instructions 🧩

### Requirements

* Python 3.10+
* pip
* OpenAI API key (for LLM and audio TTS)
* Optional: virtual environment

### Installation

```bash
# Clone the repository
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day32_AI_Audio_Tour_Agent

# Optional: create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### Run instructions

```bash
streamlit run ai_audio_tour_agent.py
```

### Usage

* Enter your OpenAI API key in the sidebar
* Specify your location and areas of interest
* Select desired tour duration (15, 30, or 60 minutes)
* Start the tour and listen to dynamically generated, expressive audio content

## Real-World Use Cases 🧭

* **Tourists and travelers**: Experience self-guided, personalized tours at their own pace
* **Museums and cultural sites**: Provide dynamic, adaptive audio guides to visitors
* **City tour operators**: Enhance offerings with automated, customizable audio tours
* **Language learners**: Explore real-world locations while listening to engaging content

## Repository Info 📁

* **Project Name:** Self-Guided AI Audio Tour Agent
* **Day Number:** Day 32
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack:** Python, Streamlit, OpenAI Agents SDK, GPT-4o Mini Audio, Web search
* **License:** MIT
