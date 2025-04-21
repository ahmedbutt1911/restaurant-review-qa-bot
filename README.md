# 🤖 restaurant-review-qa-bot

> **Local AI Chatbot** that answers questions about a pizza restaurant using LangChain, Ollama, and Chroma with realistic customer review data.

---

## 📌 Overview

This project is an intelligent, **locally-hosted AI chatbot** built using the **Retrieval-Augmented Generation (RAG)** approach. It answers user questions based on real restaurant reviews — all **without needing an internet connection** once set up.

It integrates the following key technologies:

- 🧠 **LangChain** for chaining and managing the flow of data between components  
- 🤖 **Ollama** with **LLaMA 3.2**, a local LLM for generating human-like responses  
- 📦 **Chroma** for storing and retrieving vectorized reviews  
- 🧬 **Ollama Embeddings** to semantically embed textual data  
- 📊 **Pandas** for data preprocessing  

---

## 🧠 How It Works

1. **Loads and embeds** a dataset of restaurant reviews from a CSV file.
2. Stores them in a **Chroma** vector database.
3. On user input, the bot retrieves the **top 5 most relevant reviews**.
4. Combines the question + reviews and sends them to **LLaMA 3.2** for response generation.

---



