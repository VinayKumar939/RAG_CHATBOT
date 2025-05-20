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


## 📦 Project Structure

├── rag_pipeline/         # Main logic: chunking, embedding, retrieval
├── utils/                # Helper functions
├── main.py               # Entry point
├── requirements.txt      # Dependencies
├── .env.example          # Example environment variables
├── README.md             # This file
└── tests/                # Unit and integration tests


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

### How to Run the App**
### Running the App
```bash python main.py

### Sample Use Case


###Contributors
- Vinay Kumar Mannava








   





