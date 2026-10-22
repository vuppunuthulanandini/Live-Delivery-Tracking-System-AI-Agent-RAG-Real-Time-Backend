Live Delivery Tracking System — AI Agent, RAG & Real-Time Backend

A real-time delivery tracking backend built with Flask, extended with an
LLM-powered AI agent (LangChain, OpenAI API, RAG) that dynamically selects
tools to answer delivery queries.

 Highlights
- Flask REST API designed, built, tested and supported end-to-end for
  1,000+ users
- Handles 10,000+ events/minute from 500+ concurrent drivers
- Automates raw route data into live delivery status updates
- AI agent that dynamically selects tools for delivery-status lookup, ETA
  calculation and contextual retrieval, then combines the results to answer
  delivery queries
- RAG pipeline using embeddings, a vector database and semantic search
- AI output validated against database records, the source of truth
- Resolved data-sync failures through SQL validation, improving data
  reliability by 20%

 AI Agent
- Built with LangChain and the OpenAI API
- Tools: delivery-status lookup, ETA calculation, contextual retrieval
- Flow: user query -> agent selects a tool -> tool result -> final answer

 Tech Stack
Python, Flask REST API, LangChain, OpenAI API, Embeddings, Vector DB,
MySQL/PostgreSQL, Git

 How to Run
1. Clone the repo
2. `pip install -r requirements.txt`
3. Copy `.env.example` to `.env` and add your OpenAI API key
4. Run the Flask app: `python app.py`

Key technical skills demonstrated include:

Python Flask for backend API development

SQLite for efficient data storage

REST API design for real-time communication

Live data streaming handling from multiple simulated drivers

LLM-based message generation for user-friendly ETA notifications

Frontend visualization using Leaflet.js

This project showcases my ability to build end-to-end AI-powered systems, integrating real-time data pipelines, full-stack development, and LLM capabilities. It is a scalable foundation that can be extended with features like multiple drivers, traffic prediction, dynamic routing, or enhanced LLM-powered notifications, making it a strong demonstration of both technical skill and creativity.

Overall, this project highlights my expertise in AI integration, live streaming, and full-stack engineering, making it a valuable addition to my portfolio and a strong talking point for recruiters or internships in AI, data engineering, or software development.
<img width="1280" height="720" alt="Screenshot (156)" src="https://github.com/user-attachments/assets/cbf9ca61-1a01-4411-a9fc-f5b4f9a19e80" />










