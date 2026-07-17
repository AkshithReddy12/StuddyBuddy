# 📚 Study Buddy – AI-Powered Adaptive Personal Tutor

Study Buddy is an AI-powered adaptive learning platform that delivers personalized educational support using Retrieval-Augmented Generation (RAG). The system analyzes a student's academic performance and provides explanations tailored to their learning level while generating context-aware answers from course materials.

---

## 🚀 Features

- 🎯 Personalized tutoring based on student proficiency (Beginner, Intermediate, Advanced)
- 🤖 AI-powered question answering using Google's Gemini API
- 📖 Retrieval-Augmented Generation (RAG) for grounded responses
- 🔍 Semantic search using vector embeddings
- 📂 Knowledge base built from course documents
- ⚡ Fast document retrieval using ChromaDB
- 🌐 Interactive web interface built with Streamlit

---

## 🛠️ Tech Stack

- Python
- LangChain
- Google Gemini API
- ChromaDB
- Streamlit
- Sentence Transformers
- RAG (Retrieval-Augmented Generation)

---

## 🏗️ System Architecture

```
Student
   │
   ▼
Streamlit Interface
   │
   ▼
Performance Analyzer
   │
   ▼
Student Level Classification
(Beginner / Intermediate / Advanced)
   │
   ▼
User Question
   │
   ▼
Embedding Model
   │
   ▼
ChromaDB Vector Store
   │
   ▼
Relevant Document Retrieval
   │
   ▼
Gemini LLM
   │
   ▼
Personalized Answer
```

---

## 📂 Project Workflow

1. Upload course materials.
2. Split documents into chunks.
3. Generate vector embeddings.
4. Store embeddings in ChromaDB.
5. Classify student's learning level.
6. Retrieve relevant content using semantic search.
7. Generate personalized answers using Gemini.

---

## 📊 Key Highlights

- Personalized explanations for **3 learning levels**
- Indexed **500+ course documents**
- Semantic vector search for accurate retrieval
- Reduced hallucinations through RAG
- Context-aware AI responses
- Modular and scalable architecture

---

## 📸 Screenshots

> Add screenshots of:
- Home Page
- Chat Interface
- Student Level Selection
- AI Response
- Knowledge Base Upload

---

## 📁 Project Structure

```
StudyBuddy
│
├── app.py
├── requirements.txt
├── data/
├── embeddings/
├── chroma_db/
├── models/
├── utils/
├── prompts/
├── images/
└── README.md
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/StudyBuddy.git
```

Move into the project

```bash
cd StudyBuddy
```

Create virtual environment

```bash
python -m venv venv
```

Activate virtual environment

Windows

```bash
venv\Scripts\activate
```

Linux / Mac

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---
