# MindWIKI

MindWIKI is an AI-powered study assistant and personal knowledge base. It helps you generate study plans, curate learning resources, and chat with your own PDFs and notes.

## Features

- AI-generated study plans based on your goals  
- Resource curation using external search APIs  
- Chat over PDFs and documents (RAG-style)  
- Simple web dashboard with authentication

## Tech Stack

- Frontend: Next.js (App Router), TypeScript, Tailwind CSS  
- Backend: Node.js, Express, MongoDB  
- AI: Groq API, embeddings + retrieval

## Local Development

1. Copy `.env.example` to `.env` and fill in your own keys.  
2. Build and run with Docker:

docker compose build
docker compose up -d

text

Frontend runs on `http://localhost:3000`, backend on `http://localhost:8000`.
