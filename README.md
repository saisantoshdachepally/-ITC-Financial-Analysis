📊 ITC Financial Analysis with AI Scraping & LLM Integration
🧠 Overview
This project enables users to explore ITC's financial data through intelligent question-answering using semantic search and large language models (LLMs). By scraping and embedding ITC’s financial reports, press releases, and stock data, users can ask questions like:

What was ITC’s revenue in 2024?

Is ITC’s revenue trending upward (2023 vs. 2024)?

The system retrieves the most relevant context and provides intelligent answers using modern AI techniques.

🚀 Features
🔍 Semantic Search: Retrieves the most relevant documents using SentenceTransformer embeddings and ChromaDB.

📑 PDF Scraping: Tavily API scrapes ITC financial data from web sources.

🌐 Interactive Web Interface: Built using Streamlit for user-friendly querying and result visualization.

📦 Document Storage: Stores extracted content and embeddings in ChromaDB and SQLite.

🧠 Model Integration: Uses Sentence-Transformers and LLMs for understanding and answering queries.

⚡ Fast Retrieval: Optimized querying using Chroma vector store for speed and relevance.

📈 Financial Reasoning: Capable of answering questions about trends, revenue, stock prices, and profitability.

🛠️ Technologies Used
Tavily API: For scraping PDFs and extracting text from ITC’s investor pages.

Streamlit: For creating the interactive web interface.

LangChain: For building the retrieval-based QA pipeline.

ChromaDB: As a local vector database for embedding storage and similarity search.

SQLite: For storing raw document text and metadata.

Sentence-Transformers: For converting text content into high-dimensional semantic embeddings.

Google Generative AI (or Hugging Face Transformers): For optional LLM-based question answering and summarization.

🧪 Example Questions
🧾 What was ITC’s revenue in 2024?

💰 What was ITC’s profitability in 2023?

📈 Is ITC’s revenue trending upward (2023 vs. 2024)?

📉 What was ITC’s stock price on May 10, 2025?

🔄 Workflow
Scrape Documents → Using Tavily API to fetch PDFs and HTML content from ITC’s investor portal.

Extract & Clean Text → Convert PDF/HTML content to plain text.

Generate Embeddings → Use SentenceTransformer or Google AI to embed documents.

Store in ChromaDB → Save document embeddings with metadata for retrieval.

Build Streamlit App → Let users ask natural language questions.

Retrieve + Respond → Return answers using nearest neighbors + optional LLM summarization.
