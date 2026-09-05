# RAG Project

A simple Retrieval-Augmented Generation (RAG) project built with Python.

## Overview

This project demonstrates how to build a basic RAG pipeline that:

1. Reads documents from a folder.
2. Extracts text from PDF files.
3. Splits the text into smaller chunks.
4. Generates embeddings using Sentence Transformers.
5. Stores the chunks and embeddings in ChromaDB.
6. Performs semantic search to retrieve relevant information.
7. Sends the retrieved context to an OpenAI model.
8. Generates an answer based on the retrieved context.

## RAG Flow

```text
Documents
    ↓
Text Extraction
    ↓
Text Chunking
    ↓
Embeddings
    ↓
ChromaDB
    ↓
Semantic Search
    ↓
Relevant Context
    ↓
OpenAI
    ↓
Final Answer
```

## Technologies Used

* Python
* ChromaDB
* Sentence Transformers
* PyPDF2
* OpenAI API
* python-docx

## Project Structure

```text
RAG-Project/
│
├── docs/
│   └── PDF documents
│
├── rag.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

## Setup

Create and activate a virtual environment, then install the dependencies:

```bash
pip install -r requirements.txt
```

Create a `.env` file and add your OpenAI API key:

```text
OPENAI_API_KEY=your_api_key_here
```

Then run the notebook and follow the RAG pipeline step by step.

## Note

This project is created for learning and understanding the fundamentals of Retrieval-Augmented Generation (RAG).
