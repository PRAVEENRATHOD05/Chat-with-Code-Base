# Chat with Codebase – RAG Application

This project is a Retrieval-Augmented Generation (RAG) based application that
allows users to ask natural language questions about a GitHub codebase.
The system retrieves relevant code snippets and uses them as context to
generate accurate answers.

---

## Project Overview

The goal of this project is to build a practical tool that helps users
understand large codebases more easily. Instead of manually searching files,
users can ask questions and receive context-aware explanations based on the
actual source code.

---

## Key Features

- Question-answering over a GitHub code repository
- Semantic code chunking at function and class level
- Vector-based retrieval for relevant code context
- Context-aware responses using a large language model
- Simple web-based chat interface

---

## Tech Stack

### Frontend
- React (Vite)
- CSS
- Axios

### Backend
- Python
- Flask (API)
- LangChain
- Vector database (Pinecone)
- Embedding model (nomic-embed-text)
- Large Language Model (Google Gemini)

---

## How It Works

1. A GitHub repository is cloned and processed
2. Source code files are split into meaningful chunks
3. Code chunks are converted into embeddings and stored in a vector database
4. User questions are matched against relevant code chunks
5. Retrieved code context is passed to the LLM to generate answers

---

## Setup (Local)

### 1. Clone the repository
```bash
git clone https://github.com/your-username/chat-with-codebase.git
