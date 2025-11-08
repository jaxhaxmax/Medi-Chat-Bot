🧠 Medi-Chat-Bot
An AI-Powered Medical Assistant built with LangChain, HuggingFace, and Groq

🚀 Overview

Medi-Chat-Bot is an intelligent medical chatbot that helps users with general health-related queries through a conversational interface.
It leverages Large Language Models (LLMs) from HuggingFace (served via Groq API) and integrates LangChain for context-aware responses with FAISS for efficient vector-based retrieval.
A Streamlit frontend delivers a clean, interactive user experience.

💡 Features

✨ Conversational Medical Assistant — Engages naturally with users on general medical and symptom-related questions.
🧠 Contextual Understanding — Uses FAISS vector search to recall and reason over relevant information.
⚙️ Efficient LLM Backend — Employs Groq’s accelerated inference for fast, accurate responses.
💬 Streamlit UI — Lightweight web interface for real-time chat.
📚 Local Knowledge Base Support — Can integrate PDFs, articles, or datasets for domain-specific expertise.
🧩 Modular Architecture — Independent layers for embeddings, retrieval, and generation ensure clean extensibility.


🏗️ Tech Stack
Layer	Technology
Frontend	Streamlit
Backend	Python
AI / ML	LangChain, HuggingFace, Groq
Vector Store	FAISS
Embeddings	HuggingFace Sentence Transformers
Deployment	Localhost / Streamlit Cloud


🧩 How It Works

1️⃣ User Input
The user types a medical query (e.g., “What are the symptoms of diabetes?”).

2️⃣ Embedding & Retrieval
The query is converted into embeddings via HuggingFaceEmbeddings.
FAISS searches for semantically similar medical knowledge snippets.

3️⃣ Response Generation
The retrieved context and user query are sent to the Groq-powered LLM through LangChain, generating a medically relevant and human-like response.

4️⃣ Display
The Streamlit UI renders the chatbot’s reply instantly in a friendly chat format.
