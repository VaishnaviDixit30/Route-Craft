
**RouteCraft – AI-Powered Multi-Agent Travel Planner**

RouteCraft is an AI-powered travel planning system that generates personalized itineraries using LangGraph, LangChain, Python, and the Groq API.
It uses a multi-agent architecture to coordinate destination analysis, budget planning, activity suggestions, and itinerary generation — creating a smooth, intelligent, and user-focused travel experience.

🚀 Features
🧠 Multi-Agent AI System

Agents for destination selection, cost estimation, activities, and full itinerary creation

Workflow orchestration powered by LangGraph

🤖 LangChain Integration

Prompt engineering

Structured message handling

Flexible and modular pipelines

⚡ Powered by Groq API

Lightning-fast response generation

Reliable inference for real-time suggestions

🗺️ Personalized Travel Plans

Tailored itineraries based on:

Travel dates

Budget

Location

Preferred activities

Duration

📦 Clean & Modular Codebase

Organized into agents, workflows, and utilities

Easy to upgrade or extend

📁 Project Structure
RouteCraft/
│── agents/
│   ├── destination_agent.py
│   ├── itinerary_agent.py
│   ├── budget_agent.py
│   └── activity_agent.py
│
│── workflows/
│   ├── travel_graph.py
│   └── orchestration.py
│
│── utils/
│   ├── prompts.py
│   └── helpers.py
│
│── main.py
│── requirements.txt
│── README.md

🧩 How It Works

User provides travel preferences

AI agents begin parallel + sequential tasks

LangGraph orchestrates interactions and task flow

LangChain handles prompts and message passing

Groq API powers the model to generate fast and accurate suggestions

A complete itinerary is returned as the final output

🖥️ Tech Stack

Python

LangChain

LangGraph

Groq API

AI Agents

Prompt Engineering

🛠️ Installation
git clone https://github.com/yourusername/RouteCraft.git
cd RouteCraft
pip install -r requirements.txt

Set your environment variable:
export GROQ_API_KEY="your_api_key_here"


(Windows users can use:
setx GROQ_API_KEY "your_api_key_here")

▶️ Run the App
python main.py

📸 Demo (Optional)

You can add screenshots or a sample output here:

![RouteCraft Demo](images/demo.png)

🛤️ Future Enhancements

Add a web UI (React / Flask)

Real-time travel data (flights, hotels, maps)

Offline support for low-connectivity regions

User profile memory + preferences
