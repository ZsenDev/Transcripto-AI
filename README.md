# TranscriptoAI - Video/Audio Transcription & Summarizer Project

## Tech Stack
- Frontend: React + Vite + Tailwind CSS
- Backend: FastAPI + PostgreSQL + Redis + MinIO
- AI: OpenAI Whisper (for transcription), Hugging Face BART (for summarization)
- Async Tasks: Celery + Redis
- Containerization: Docker + docker-compose

## Setup
1. Clone repo  
2. Run docker-compose up --build  
3. Frontend: http://localhost:3333  
4. Backend: http://localhost:8000  

## Features
- Upload audio/video files
- Transcription & summarization processing
- Store results & files securely
- API endpoints for frontend consumption

## Dashboard
![Dashboard Overview](Images/TranscriptoAI%201.jpeg)

![Upload UI](Images/TranscriptoAI%202.jpeg)

![Summary View](Images/TranscriptoAI%203.jpeg)
