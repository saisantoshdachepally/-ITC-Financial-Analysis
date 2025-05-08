# -ITC-Financial-Analysis

Use Case: ITC Financial Analysis with AI Scraping & LLM Integration 
Overview
This project allows users to search through  ITC Financial Analysis questions and answers using semantic search. It leverages LangChain and Chroma to process text embeddings and retrieve the most relevant answers based on user queries.

The app provides an interactive interface where users can input a query, and it returns the most relevant documents (questions, answers) based on semantic search using SentenceTransformers and ChromaDB.

Technologies Used
Tavily API: this api used for the scrapping the pdfs

Streamlit: Web framework for building the interactive app.

LangChain: To build the pipeline for semantic search.

ChromaDB: For storing and querying the document embeddings.

Sentence-Transformers: For generating text embeddings from the documents.

Google Generative AI Embeddings: For generating embeddings of the documents and queries.

Features
Tavily API: this api used for the scrapping the pdfs

Interactive Web Interface: Built using Streamlit.

Semantic Search: Provides relevant answers to user queries using embedding-based search with ChromaDB.

Document Storage: Stores document embeddings and metadata in ChromaDB for fast retrieval.

Model Integration: Uses Google Generative AI model for embedding-based search.

