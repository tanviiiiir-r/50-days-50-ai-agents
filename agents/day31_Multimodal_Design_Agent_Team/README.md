# Multimodal AI Design Agent Team 🎨🤖

## Problem 💡

Designers and product teams often struggle to objectively evaluate UI/UX quality and compare their designs with competitors. Manual analysis is time-consuming, subjective, and often misses subtle visual or interaction issues. Market positioning insights are usually separate from design evaluation, making strategic decisions slower and less informed.

This agent team exists to provide a comprehensive, automated evaluation of product designs, combining visual analysis, UX assessment, and market intelligence — all powered by specialized AI agents using Google's Gemini model.

## Solution 🚀

The **Multimodal AI Design Agent Team** is a Streamlit application that runs multiple specialized AI agents in parallel:

* **Visual Design Agent**: Analyzes color schemes, typography, visual hierarchy, and design patterns.
* **UX Analysis Agent**: Evaluates usability, interaction patterns, user flows, and accessibility.
* **Market Analysis Agent**: Provides competitor insights, market positioning, and strategic recommendations.

Users can upload their designs and optionally competitor designs, select focus areas, and receive structured, actionable insights instantly. The system combines visual understanding with market research for a complete design evaluation.

## Features ⚙️

* Specialized AI agents for visual, UX, and market analysis
* Multiple analysis types: Visual Design, UX, Market Analysis
* Comparative analysis with competitor uploads
* Customizable focus areas for detailed evaluation
* Context-aware insights with user-provided descriptions
* Real-time processing with progress indicators
* Structured, actionable output for decision making

## Tech Stack 🧠

* **Frontend**: Streamlit
* **AI Model**: Google Gemini 2.0
* **Image Processing**: Pillow
* **Market Research**: DuckDuckGo Search API
* **Framework**: Phidata for agent orchestration

## Setup Instructions 🧩

### Requirements

* Python 3.10+
* pip
* Gemini API key from [Google AI Studio](https://aistudio.google.com/apikey)
* Optional: virtual environment

### Installation

```bash
# Clone repository
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day31_Multimodal_Design_Agent_Team

# Optional: create and activate virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### Run instructions

```bash
streamlit run design_agent_team.py
```

### Usage

* Enter your Gemini API key in the sidebar
* Upload your design files (JPG, JPEG, PNG)
* Select analysis types and focus areas
* Provide context if desired
* Click **Run Analysis** to get structured insights

## Real-World Use Cases 🧭

* **Product teams**: Rapidly evaluate new UI/UX designs and identify improvements
* **Design agencies**: Provide clients with data-driven design recommendations
* **Startups**: Compare product design against competitors and optimize market positioning
* **UX researchers**: Automate usability and accessibility assessment for prototypes

## Repository Info 📁

* **Project Name:** Multimodal AI Design Agent Team
* **Day Number:** Day 31
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack:** Python, Streamlit, Google Gemini 2.0, Pillow, DuckDuckGo API, Phidata
* **License:** MIT
