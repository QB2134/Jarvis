# Jarvis- Just a Rather Very Intelligent System.
Black-coded, memory-driven, voice-enabled, locally aligned intelligence.
<p align="center"> <img src="https://github.com/user-attachments/assets/example-logo" width="140"/> </p>

Jarvis is my fully local, privacy-preserving, personalized AI assistant built around a custom system prompt, vector memory, voice input/output, and modular tool integrations.

It runs entirely on my hardware using:

DeepSeek 32B Q4_0 (local LLM)

WSL2 + GPU acceleration

Streamlit front-end

Whisper speech-to-text

Edge TTS

DuckDuckGo search tools

JSON + embeddings memory system

Jarvis behaves as a personal AI operating system—not just a chatbot—designed for:

🧠 Intelligent dialogue
📚 Quantitative analysis & math reasoning
💻 Coding assistance (Python, C++, etc.)
🌍 Black-coded philosophical grounding
🎤 Voice-to-text & text-to-speech
📁 Persistent memory & semantic recall
🛠️ Local tools & automation

Jarvis represents my long-term vision of building an autonomous, culturally grounded, cognitively capable assistant who helps manage thinking, projects, and long-term goals.

✨ Key Features
🔊 Voice Input / Output

Whisper speech recognition (local, no cloud)

Optional “Jarvis speaks replies” using Edge TTS

Realtime audio-to-text and text-to-audio workflow

🧠 Long-Term Memory System

JSON-based memory store

Automatic semantic embeddings with SentenceTransformers

Vector similarity search

“Relevant past memories” injection into context

Memory editing interface in Streamlit

🔍 Web Search Tools

DuckDuckGo local search API wrapper

Web results injected into LLM reasoning

🤖 Custom Jarvis System Prompt

A deeply personalized alignment spec featuring:

Black-coded, African-grounded worldview

Philosophy, decolonial theory, and strategy

Quantitative finance + math expert mode

Coding assistant mode

Life organization + executive function support

General dialogue mode

This is the “consciousness core” of Jarvis.

💬 Streamlit Chat UI

Multi-mode selection

Chat history

Voice uploads

Real-time streaming responses

Live memory viewer/editor

🔐 Fully local

No cloud calls.
No telemetry.
No data leaks.
Everything stays on my machine.
  
🔧 Installation Instructions
1️⃣ Install Ollama

https://ollama.com/download

Then pull the model:

ollama pull deepseek-r1-32b-q4_0 


Or load a local .gguf file via a Modelfile.

2️⃣ Create a virtual environment
python -m venv .venv
.\.venv\Scripts\activate
pip install -r requirements.txt

3️⃣ Run Jarvis:
streamlit run jarvis.py

4️⃣ (Optional) One-click launcher

A .bat file is included:

start "" "C:\Windows\System32\wsl.exe" -d Ubuntu -u root ollama serve
timeout /t 2
streamlit run jarvis.py

jarvis/
│
├── jarvis.py                  # Main application
├── memory.json                # Long-term memory store
├── requirements.txt           # Python dependencies
├── launcher/
│   ├── jarvis_launch.bat      # Windows launcher
│   ├── icon.ico               # Desktop icon
├── models/
│   └── (place local gguf here - optional)
└── README.md

🧠 Jarvis Modes
1. General Dialogue

Natural conversation, emotional intelligence, contextual grounding.

2. Philosophy / Black Thought

Grounded analysis drawing from:

Fanon

Nkrumah

Biko

Malcolm X

CLR James
…and others.

3. Quant / Math

Calculus, linear algebra, probability

Stochastic models

Pricing, econometrics

Step-by-step derivations

LaTeX-style answers

4. Coding / Projects

Python, C++, algorithms, debugging, refactoring.

5. Life / Systems

Study design
Habit loops
Deep work structure
Cognitive load reduction

6. Meta / Reflection

Tracks long-term goals:

Becoming a quant

Mathematical mastery

Personal development

Power-building for Black communities

🚀 Roadmap
🧠 Personality & Behavior

Background reasoning mode

Emotional tone control

Auto-personality evolution

Daily summary generator

📘 Memory Expansion

FAISS or ChromaDB backend

Auto-tagging & embeddings

Knowledge graph structure

📊 Quant Tools

Custom symbolic math engine

Simulation engine (Monte Carlo / SDEs)

Quant notebook integration

🗂️ UI Improvements

Chat timeline

Memory browser 2.0

Voice hotword detection (“Hey Jarvis”)

📄 License

MIT License — free for personal and academic use.

⭐ Why This Project Exists

Jarvis is part of my long-term journey:

Becoming a high-level quant

Building deeply personalized AI systems

Advancing Black-centered computational tools

Mastering machine learning from fundamentals

Laying a foundation for future AGI projects

This project is personal, cultural, technical, and aspirational — and it will continue growing as I grow.
