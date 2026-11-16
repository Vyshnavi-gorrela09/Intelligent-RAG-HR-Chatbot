# Intelligent RAG-Based HR Help Desk Chatbot

## Project Overview
An AI-powered HR Help Desk chatbot developed as part of the Intelligent RAG Challenge for Zyro Dynamics.

The chatbot uses Retrieval-Augmented Generation (RAG) to answer employee queries based on HR policy documents.

## Tech Stack
- Python
- LangChain
- FAISS
- Sentence Transformers
- Gemini API
- Streamlit

## Key Features
- HR document processing and text chunking
- Semantic embeddings generation
- FAISS-based vector search
- Context-aware AI-generated responses
- Out-of-scope query handling

## Workflow
1. Load HR policy documents.
2. Extract and split text into chunks.
3. Generate embeddings.
4. Store embeddings in FAISS.
5. Retrieve relevant document context.
6. Generate answers using Gemini.

## Project Structure
- `Intelligent_RAG_Challenge.ipynb` – Main implementation
- `submission.csv` – Challenge submission

## Objective
To build an intelligent HR assistant that provides employees with accurate and relevant answers from company HR policies.

## Author
Phani Vyshnavi Gorrela
