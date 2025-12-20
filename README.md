# WonderWise — Multi‑Agent Travel Planner

A Windows‑safe, Streamlit‑based multi‑agent travel planner using LangGraph.
Agents collaborate via a shared state and use Google (Serper) search for research.

## Setup
1. Create venv and install deps:
   pip install -r requirements.txt
2. Set env vars:
   GROQ_API_KEY=...
   SERPER_API_KEY=...
3. Run:
   streamlit run app.py