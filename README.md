# LangChain RAG with Gemini Pro – Space Tourism Project

This project demonstrates a Retrieval-Augmented Generation (RAG) system using **LangChain**, **FAISS**, **HuggingFace Embeddings**, and **Google's Gemini Pro**.

We use a custom `.txt` file (`space_tourism_future.txt`) as a knowledge base. Users can ask conversational questions about the topic, and the Gemini-powered chatbot retrieves and answers based on document chunks.

---

##  Features

- Document ingestion with `TextLoader`
- Chunking with `RecursiveCharacterTextSplitter`
- Vector storage using `FAISS`
- Text embeddings using Hugging Face Transformers
- Question answering via Gemini Pro (`gemini-pro`)
- Chat memory using `ConversationalRetrievalChain`
