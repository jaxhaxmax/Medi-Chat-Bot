🧠 Medi-Chat-Bot
An AI-Powered Medical Assistant built with LangChain, HuggingFace, and Groq
🚀 Overview

Medi-Chat-Bot is an intelligent medical chatbot designed to assist users with general health-related queries in a conversational way.
It uses Large Language Models (LLMs) from HuggingFace via Groq’s API, integrated with LangChain for context-aware responses and FAISS for efficient vector-based retrieval.
The frontend is powered by Streamlit, providing a clean, interactive user interface.

💡 Features

✅ Conversational Medical Assistant — Engages in natural dialogue with users on general health and symptom queries.
✅ Contextual Understanding — Uses FAISS vector search to retrieve relevant context before answering.
✅ Efficient LLM Backend — Runs inference using Groq API and HuggingFace models.
✅ Streamlit UI — Simple web interface for seamless chatbot interaction.
✅ Local Knowledge Base Support — Can integrate custom PDFs, articles, or documents for domain-specific responses.
✅ Modular Codebase — Separate logical blocks for embeddings, retrieval, and response generation.

🏗️ Tech Stack
Layer	Technology
Frontend	Streamlit
Backend	Python
AI/ML	LangChain, HuggingFace, Groq
Vector Store	FAISS
Embeddings	HuggingFace Sentence Transformers
Deployment	Localhost / Streamlit Cloud