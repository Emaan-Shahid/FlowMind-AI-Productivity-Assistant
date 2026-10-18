# 🧠 FlowMind AI - AI Productivity Assistant

An intelligent AI-powered productivity assistant that combines **Retrieval-Augmented Generation (RAG)** with automated AI tools to help users understand, summarize, and transform documents into useful outputs.

Built using **Python, Streamlit, FAISS, LangChain, and Google Gemini**.

---

# 🚀 Features

## 📄 Document Intelligence (RAG)

- Upload PDF, DOCX, and TXT documents
- Automatic document processing and chunking
- Semantic search using FAISS vector database
- Context-grounded answers using Gemini
- Source-aware responses with citations

---

## 🧠 Intelligent Tool Selection

FlowMind AI automatically detects user intent and selects the appropriate AI tool.

Supported tools:

### 📌 Summary Assistant

Automatically summarizes uploaded documents.

Example:

```
Summarize this document
```

---

### ✉️ Email Generator

Creates professional emails from document content.

Example:

```
Create an email explaining this paper
```

---

### ✅ Todo Generator

Extracts actionable tasks from documents.

Example:

```
Create a todo list from this document
```

---

### ⚡ Workflow Automation

Creates a complete productivity workflow:

- Summary
- Action items
- Email draft

Example:

```
Create a workflow from this document
```

---

# 🏗️ Architecture

```
User
 |
 |
Streamlit Interface
 |
 |
Intent Router
 |
 |----------------|
 |                |
RAG Pipeline      AI Tools
 |                |
FAISS             Summary
Vector DB         Email
 |                Todo
Gemini            Workflow
 |
Response + Sources
```

---

# 🛠️ Tech Stack

## Programming

- Python 3.10+

## AI / LLM

- Google Gemini
- LangChain
- Retrieval-Augmented Generation (RAG)

## Vector Database

- FAISS

## Frontend

- Streamlit

## Document Processing

- PyPDF
- DOCX Loader
- Text Processing

---

# 📂 Project Structure

```
FlowMind AI

│
├── app.py
├── rag_pipeline.py
├── pdf_loader.py
├── chat_store.py
│
├── tools
│   ├── router.py
│   ├── summary_tool.py
│   ├── email_tool.py
│   ├── todo_tool.py
│   └── workflow.py
│
├── requirements.txt
├── README.md
└── .env
```

---

# ⚙️ Installation

Clone the repository:

```bash
git clone YOUR_GITHUB_LINK
```

Navigate:

```bash
cd FlowMind-AI
```

Create virtual environment:

```bash
python -m venv venv
```

Activate:

Windows:

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# 🔑 Environment Setup

Create a `.env` file:

```
GOOGLE_API_KEY=your_api_key_here
```

---

# ▶️ Run Application

Start Streamlit:

```bash
streamlit run app.py
```

Open:

```
http://localhost:8501
```

---

# 📸 Demo Workflow

1. Upload a document
2. Ask questions about the document
3. Generate summaries
4. Extract tasks
5. Create emails
6. Run automated workflows

---

# 🎯 Project Goal

FlowMind AI demonstrates how modern AI systems can combine:

- Retrieval-Augmented Generation
- Large Language Models
- Vector Search
- Intelligent Routing
- AI Automation

to create practical productivity applications.

---

# 👩‍💻 Author

Emaan Shahid

BS Computer Science  
University of Central Punjab

GitHub:
https://github.com/Emaan-Shahid

LinkedIn:
https://www.linkedin.com/in/emaan-shahid/
