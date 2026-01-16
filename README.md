# INTROVERTOR – AI Interview System

INTROVERTOR is an AI-powered interview and personality analysis system that
conducts adaptive interviews based on resume content and evaluates answers
using NLP techniques.

## Features
- Resume-based dynamic interview questions
- AI-driven question generation
- Personality & confidence analysis
- Scoring and selection probability
- Web-based interface (Gradio)

## Tech Stack
- Python 3
- NLP (NLTK)
- Hugging Face Inference API
- Gradio (Web UI)
- PDF Resume Parsing

## Project Structure
INTROVERTOR/
├── app.py
├── ai_engine.py
├── resume_parser.py
├── scoring.py
├── memory.json
└── requirements.txt

## How to Run
1. Install dependencies:
   pip install -r requirements.txt
2. Run the app:
   python app.py
3. Open browser at:
   http://127.0.0.1:7860

## Future Scope
- Voice-based interview
- Facial emotion detection
- Company-specific interview modes
- Cloud deployment
