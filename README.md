# AI Research Assistant

An AI-powered research assistant that helps users understand academic papers more efficiently. The application allows users to upload research papers, generate concise summaries, extract key contributions, and ask questions about the content using Retrieval-Augmented Generation (RAG) and open-source Large Language Models.

The project is being developed as a production-ready full-stack application with user authentication, persistent chat history, and a personalized research library.

---

## Features

- Secure user authentication
- Upload and manage research papers (PDF)
- Automatic text extraction and preprocessing
- AI-generated research paper summaries
- Key contribution and insight extraction
- Question Answering using Retrieval-Augmented Generation (RAG)
- Conversation history for each uploaded paper
- Personal research library for every user
- Prompt engineering experiments for summary comparison
- User feedback collection and evaluation

---

## Tech Stack

### Frontend
- Streamlit

### Backend
- FastAPI
- Python

### Database & Storage
- Supabase PostgreSQL
- Supabase Authentication
- Supabase Storage

### AI & NLP
- LangChain
- Ollama
- Open Source LLMs (Gemma / Qwen)
- ChromaDB
- Sentence Transformers
- spaCy
- PyMuPDF

---

## Project Structure

```text
AI-Research-Assistant/
│
├── backend/
│   ├── api/
│   ├── auth/
│   ├── database/
│   ├── models/
│   ├── prompts/
│   ├── rag/
│   ├── services/
│   ├── utils/
│   └── main.py
│
├── frontend/
│   └── streamlit_app.py
│
├── docs/
├── tests/
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Project Workflow

```
User Login
      │
      ▼
Upload Research Paper
      │
      ▼
Extract Text
      │
      ▼
Text Preprocessing
      │
      ▼
Generate Embeddings
      │
      ▼
Store in Vector Database
      │
      ▼
Generate Summary
      │
      ▼
Extract Key Contributions
      │
      ▼
Question Answering (RAG)
      │
      ▼
Save Conversation History
```

---

## Planned Modules

- [ ] User Authentication
- [ ] PDF Upload
- [ ] PDF Text Extraction
- [ ] NLP Preprocessing
- [ ] Embedding Generation
- [ ] ChromaDB Integration
- [ ] Research Paper Summarization
- [ ] Key Contribution Extraction
- [ ] Research Paper Q&A
- [ ] Chat History
- [ ] Prompt Comparison Dashboard
- [ ] User Feedback System
- [ ] Deployment

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/AI-Research-Assistant.git

cd AI-Research-Assistant
```

### Create a virtual environment

```bash
python -m venv venv
```

Activate the environment

**Windows**

```bash
venv\Scripts\activate
```

**macOS/Linux**

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the FastAPI backend

```bash
uvicorn backend.main:app --reload
```

### Run the Streamlit frontend

```bash
streamlit run frontend/streamlit_app.py
```

---

## Current Development Status

This project is currently under active development.

The first phase focuses on setting up the application architecture, authentication, database design, and backend APIs. Future phases will introduce document processing, retrieval-augmented generation, prompt engineering experiments, and deployment.

---

## Future Improvements

- Multi-document question answering
- Citation-aware responses
- Semantic search across papers
- Research paper recommendations
- AI-generated study notes
- Export summaries as PDF
- Team collaboration and shared workspaces
- Research analytics dashboard

---


## Author

**Prerna Sharma**

If you have any suggestions or feedback, feel free to open an issue or contribute to the project.