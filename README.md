# 🤖 RAG-Application (n8n + Docker)

This project is a *Retrieval-Augmented Generation (RAG) application* built using *n8n*.  
It allows you to connect data sources, retrieve context, and enhance responses from Large Language Models (LLMs) using *custom RAG workflows*.  

The project runs locally via *Docker* (with Docker Compose for persistence).

---

## 🚀 Features
- 🔍 *RAG Workflow* – Retrieve relevant documents and feed them into LLMs  
- ⚡ *Automated Pipelines* – Built entirely with *n8n workflows*  
- 🐳 *Dockerized Setup* – Easy to run and manage  
- 📚 *Custom Knowledge Base* – Plug in your own datasets (PDF, text, APIs)  
- 🔧 *Extensible* – Add integrations with databases, APIs, or vector stores  

---

## 🛠 Tech Stack
- *n8n* – Workflow automation and orchestration  
- *Docker & Docker Compose* – Containerized setup with persistence  
- *LLMs* – (OpenAI API, HuggingFace, or any supported provider)  
- *Vector Database* – (FAISS, Pinecone, Chroma, or others configured in workflow)  

---

## ⚙ Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/AdarshGupta2112/RAG-Application.git
cd RAG-Application
