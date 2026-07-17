# 📚 Study Buddy – AI-Powered Adaptive Personal Tutor

Study Buddy is an AI-powered adaptive learning platform that leverages Retrieval-Augmented Generation (RAG) to provide personalized educational support. It answers students' questions using course materials and adapts explanations based on their proficiency level, creating a more effective and engaging learning experience.

---

# ❗ Problem Statement

Most Learning Management Systems (LMS) provide course materials, assignments, and recorded lectures but lack an intelligent assistant to help students resolve their doubts instantly. Students often spend significant time searching through lengthy notes or waiting for instructor support, making the learning process inefficient and less personalized.

---

# 💡 Solution

Study Buddy addresses this challenge by combining **Retrieval-Augmented Generation (RAG)**, **LangChain**, **Gemini API**, and **ChromaDB** to deliver accurate, context-aware answers directly from course materials. The system analyzes a student's academic performance and generates personalized explanations tailored to three learning levels: **Beginner, Intermediate, and Advanced**.

---

# 🎯 Project Outcomes

- Personalized explanations based on each student's learning level.
- Instant AI-powered doubt resolution from course materials.
- Reduced hallucinations using Retrieval-Augmented Generation (RAG).
- Improved answer relevance through semantic search and vector embeddings.
- Grounded responses using a knowledge base of **500+ course documents**.
- Faster access to relevant study material without manual searching.

---

# 🚀 Features

- 🎯 Adaptive tutoring for three proficiency levels
- 🤖 AI-powered question answering using Gemini API
- 📖 Retrieval-Augmented Generation (RAG)
- 🔍 Semantic search using vector embeddings
- 📂 Knowledge base built from course documents
- ⚡ Fast retrieval using ChromaDB
- 🌐 Interactive Streamlit interface

---

# 🛠️ Tech Stack

- Python
- LangChain
- Google Gemini API
- ChromaDB
- Streamlit
- Sentence Transformers
- Retrieval-Augmented Generation (RAG)

---

# 🏗️ System Architecture

```text
                 Student
                    │
                    ▼
          Streamlit Web Interface
                    │
                    ▼
          Performance Analyzer
                    │
                    ▼
 Student Level Classification
(Beginner | Intermediate | Advanced)
                    │
                    ▼
             Student Query
                    │
                    ▼
          Embedding Generation
                    │
                    ▼
        ChromaDB Vector Database
                    │
                    ▼
       Semantic Document Retrieval
                    │
                    ▼
             Gemini LLM
                    │
                    ▼
     Personalized AI Response
```

---

# ⚙️ Workflow

1. Upload course materials.
2. Split documents into semantic chunks.
3. Generate vector embeddings.
4. Store embeddings in ChromaDB.
5. Determine the student's proficiency level.
6. Retrieve relevant documents using semantic search.
7. Generate a grounded, personalized response using Gemini.

---

# 📊 Key Highlights

- Personalized tutoring for **3 learning levels**
- Indexed **500+ course documents**
- Semantic vector search for relevant retrieval
- Reduced hallucinations with RAG
- Context-aware AI-generated responses
- Modular and scalable architecture

---

# 📂 Project Structure

```text
StudyBuddy/
│
├── app.py
├── requirements.txt
├── data/
├── chroma_db/
├── embeddings/
├── models/
├── utils/
├── prompts/
├── assets/
├── screenshots/
└── README.md
```

---

# ⚡ Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/StudyBuddy.git
```

### Navigate to the project

```bash
cd StudyBuddy
```

### Create a virtual environment

```bash
python -m venv venv
```

### Activate the environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the application

```bash
streamlit run app.py
```

---
