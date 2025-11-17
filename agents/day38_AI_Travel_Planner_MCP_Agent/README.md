# 🌍 MCP Travel Planner Agent Team 🧳

A sophisticated Streamlit-based AI travel planning application that creates highly detailed, personalized travel itineraries using multiple MCP servers and Google Maps integration. It leverages Airbnb MCP for real accommodation data and a custom Google Maps MCP for precise distance calculations and location services.

## 💡 Problem

Planning a trip involves complex scheduling, distance calculations, budgeting, and researching accommodations and attractions. Manual planning is time-consuming and often lacks accuracy in timing, travel distances, and cost estimations.

## 🚀 Solution

The MCP Travel Planner Agent Team automates trip planning using AI agents connected to multiple MCP servers. It generates highly detailed, personalized itineraries with real-time accommodation data, accurate travel times, cost breakdowns, and practical recommendations, all tailored to user preferences.

## ⚙️ Features

### 🤖 AI-Powered Travel Planning

* Day-by-day schedules with timings, addresses, and costs
* Personalized recommendations based on preferences and budget
* Buffer time included for travel and delays

### 🏨 Airbnb MCP Integration

* Real accommodation listings with pricing and availability
* Property details including amenities, guest reviews, and booking info
* Budget-conscious recommendations
* Direct booking information

### 🗺️ Google Maps MCP Integration

* Accurate distance and travel time calculations
* Location services for points of interest
* Transportation optimization and navigation guidance

### 🔍 Google Search Integration

* Weather forecasts with clothing recommendations
* Restaurant research with addresses, price ranges, and reviews
* Attraction details including hours, ticket prices, and best visiting times
* Local insights and cultural information

### 📅 Additional Features

* Calendar export (.ics) for Google Calendar, Apple Calendar, or Outlook
* Comprehensive cost breakdown for all trip components
* Multiple accommodation options with distances from city center

## 🧠 Tech Stack

* **Frontend**: Streamlit
* **AI Model**: GPT-4o
* **MCP Servers**: Airbnb MCP, Custom Google Maps MCP
* **Data Sources**: Google Search, Google Maps API, Airbnb API
* **Python Packages**: See `requirements.txt`

## 🧩 Setup Instructions

### Requirements

1. **API Keys**:

   * OpenAI API Key: [OpenAI Platform](https://platform.openai.com/api-keys)
   * Google Maps API Key: [Google Cloud Console](https://console.cloud.google.com/apis/credentials)
2. Python 3.8+
3. MCP Servers (auto-connected by the app)

### Installation

```bash
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day38_AI_Travel_Planner_MCP_Agent
pip install -r requirements.txt
```

### Run Instructions

```bash
streamlit run app.py
```

* Enter OpenAI and Google Maps API keys in the sidebar
* Specify destination, trip duration, budget, and preferences
* Click "🎯 Generate Itinerary"
* Optional: Download itinerary as .ics calendar file

## 🧭 Real-World Use Cases

* Personalized vacation planning for families or solo travelers
* Business travel planning with optimized routes and timing
* Adventure or cultural trips with budget-friendly accommodation suggestions
* Quick generation of detailed itineraries for travel agencies

## 📁 Repository Info

* **Project Name**: MCP Travel Planner Agent Team
* **Day Number**: 31
* **Series Name**: 50 Days, 50 AI Agents
* **Author**: [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack**: Streamlit, GPT-4o, Airbnb MCP, Google Maps MCP, Google Search
* **License**: MIT
