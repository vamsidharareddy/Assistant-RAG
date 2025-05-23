﻿# RAG-Assistant

This project leverages **Retrieval-Augmented Generation (RAG)** to build a **multi-agent question-answering assistant** that can handle a variety of queries in a smart, scalable way. The app is powered by **Streamlit** for interactive UI, **Hugging Face** for model download and management, and **Llama-Cpp** for seamlessly running the model in Python.

## Project Overview 🌍

This cutting-edge assistant integrates **multiple agents** to handle different kinds of queries:

### Agents:
- **🔍 RAG**: 
  - *Purpose*: Retrieves relevant context from documents and **generates responses** based on that context.
  - *Key Feature*: Uses **document retrieval** and the **Llama model** to answer complex queries based on real-time information.

- **🧮 CALC**: 
  - *Purpose*: Handles **math-related queries**.
  - *Key Feature*: Evaluates mathematical expressions directly from the user's input.

- **📖 DICT**: 
  - *Purpose*: Provides **word definitions** for queries asking about word meanings.
  - *Key Feature*: Uses predefined dictionary logic to return concise and accurate definitions.

## Features ✨

### ⚡️ Text-based Q&A with Llama:
- Powered by the **Llama model** for generating context-aware answers.

### 🧠 Intelligent Query Routing:
- Dynamically decides between **RAG**, **CALC**, or **DICT** based on the user's input.

### 📚 Efficient Document Retrieval:
- Integrates a **vector store** for fast document retrieval, using **Faiss** and **SentenceTransformer** for quick search and efficient answers.

### 🚧 Robust Error Handling:
- Comprehensive error handling with **real-time user feedback**, ensuring a smooth experience even when things go wrong.
