# RAG Chatbot with Feedback Loop

## 🔍 Overview
This project implements a Retrieval-Augmented Generation (RAG) system with a feedback loop. It supports document ingestion, chunking, vector storage, and response generation using LLMs.

## ⚙️ Features
-## 🔧 Features
- Chunk documents using custom logic
- Generate vector embeddings using OpenAI or Transformers
- Store vectors using FAISS or ChromaDB
- Retrieve relevant chunks for context-aware responses
- Use LangChain to build prompt chains
- Feedback loop for improving system responses

## 🧱 Architecture
 <img width="468" alt="image" src="https://github.com/user-attachments/assets/b65a5646-fbfb-4c59-b05b-7aaede9a1312" />

## Project Structure

RAG_CHATBOT/
├── data/
│   └── interviews/             ✅ Uploaded interview documents (.txt, .pdf, .docx)
│       ├── amazon_john.txt
│       ├── google_arya.pdf
│       └── tcs_ravi.docx
│
├── loaders/
│   └── document_loader.py      📄 Extracts raw text from uploaded documents
│
├── utils/
│   └── chunking.py             ✂️  Contains recursive chunking logic for splitting text
│
├── embeddings/
│   └── embedder.py             🧠 Generates embeddings from chunks (OpenAI / other models)
│
├── retriever/
│   └── faiss_retriever.py      🔍 Handles vector search and retrieval using FAISS or Chroma
│
├── scripts/
│   ├── test_chunking.py        🧪 Script to test chunking pipeline independently
│   └── test_embedding.py       🧪 (Optional) Script to test embeddings and preview vectors
│
├── main.py                     🚀 Main RAG chatbot pipeline and Streamlit/UI app
├── requirements.txt            📦 Python dependencies
├── .gitignore                  🚫 Excludes virtual envs, logs, temp files, etc.
└── README.md                   📘 Project overview, setup instructions, and usage guide


## 🛠️ Setup Instructions

###  -Clone the repo
   '''bash
      git clone  https://github.com/VinayKumar939/RAG_CHATBOT.git 
      cd RAG_CHATBOT

### -Create Virtual Environment
   python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

###  -Install Dependencies
  pip install -r requirements.txt
  
### -Configure  Environment 
Create a .env file based on .env.example with API keys, DB configs, etc.

### How to Run the App
 bash 
 python main.py

### Contributors
- Vinay Kumar Mannava








   





