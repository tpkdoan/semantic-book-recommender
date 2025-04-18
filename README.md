# Semantic Book Recommender

This is a **learning project** where I followed along with the YouTube tutorial [LLM Course – Build a Semantic Book Recommender](https://www.youtube.com/watch?v=Q7mS1VHm3Yw&t=3536s) by *@freeCodeCamp.org*.

The project is a **semantic book recommendation app** built using **Python, LangChain, Gradio**, and a **Hugging Face embedding model** (instead of OpenAI).

---

## About the Project

The app allows users to input a book title or description and get **AI-powered semantic recommendations** based on vector similarity. It uses:

- **Hugging Face embedding model** `sentence-transformers/all-MiniLM-L6-v2` for converting book text into vectors
- **FAISS** (through LangChain's Chroma) for vector storage and similarity search
- **LangChain** to manage the flow
- **Gradio** for the web interface

> ⚠This is a 100% code-along project — the code and structure closely follow the tutorial video.

---

## Tech Stack

- Python
- LangChain
- Gradio
- FAISS
- **Hugging Face model**: `sentence-transformers/all-MiniLM-L6-v2`

---

## Original Tutorial
YouTube Video: LLM Course – Build a Semantic Book Recommender

By: @freeCodeCamp.org

---

## Why I Built This
This was a hands-on way for me to explore:

- How LLM-related apps work
- How semantic search works using embeddings
- Using open-source tools instead of OpenAI (like Hugging Face models)

### 📌 Notes
- The Hugging Face model used: sentence-transformers/all-MiniLM-L6-v2
- This repo is for learning purposes only.
- All credit for the project idea and base implementation goes to the original tutorial creator.


