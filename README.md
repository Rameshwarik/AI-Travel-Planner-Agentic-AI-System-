# 🌍 AI Travel Planner (Agentic AI System)

An intelligent **multi-agent travel planning system** built using **Groq LLMs and Agno framework**, designed to generate real-time, optimized travel itineraries based on user preferences.

## 🚀 Features

* 🔍 **Research Agent** – Gathers real-time travel insights (attractions, food, tips)
* 🧠 **Summarizer Agent** – Condenses large data into structured insights
* 🧭 **Planner Agent** – Generates day-wise itinerary with budget planning
* ✅ **Reviewer Agent** – Refines and optimizes the final travel plan

## 🧠 Architecture

Multi-agent pipeline:
User Query → Research → Summarization → Planning → Review → Final Output

## 🛠️ Tech Stack

* **LLM**: Groq (LLaMA 3.1)
* **Framework**: Agno (Agent orchestration)
* **Search Tool**: DuckDuckGo Search (DDGS)
* **Frontend/UI**: Gradio
* **Language**: Python

## ⚙️ How It Works

The system uses a chain of specialized AI agents:

1. Extracts real-time information from web search
2. Summarizes key insights
3. Generates a structured itinerary
4. Optimizes output for practicality and cost

## 💡 Example Use Case

"Plan a 3-day Goa trip for beaches and nightlife"

## 📌 Key Highlights

* Multi-agent LLM system with tool integration
* Real-time information retrieval
* Context-aware itinerary generation
* Output validation and refinement

## ▶️ Run Locally

```bash
pip install agno groq ddgs gradio
python app.py
```

## 📎 Project File

Refer to implementation: 

## 🌟 Future Improvements

* Add user budget constraints as input
* Integrate map APIs for route optimization
* Add hotel & transport booking integration

---

Built with a focus on **Agentic AI, LLM orchestration, and real-world usability**
