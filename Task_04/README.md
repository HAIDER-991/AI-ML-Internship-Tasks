# Task 4: Context-Aware Chatbot Using LangChain (RAG)

## 🎯 Objective
Build a conversational chatbot that remembers context and retrieves information from
external documents using Retrieval-Augmented Generation (RAG).

## 🧠 Methodology
- Used LangChain for orchestration
- FAISS vector store for document retrieval
- HuggingFace embeddings for semantic search
- ConversationBufferMemory for context awareness
- Deployed using Streamlit

## 📊 Key Observations
- Chatbot retains conversation history
- Answers are grounded in document content
- RAG significantly reduces hallucinations


The chatbot was implemented using LangChain with Retrieval-Augmented Generation (RAG).
A FAISS vector store was used for document retrieval, and ConversationBufferMemory
enabled context-aware multi-turn conversations.
The system was tested in Google Colab.
