🚀 News Article Semantic Search using Vector Database

This project implements a semantic search system over news articles using:

Google Gemini Embeddings (gemini-embedding-001)

ChromaDB as a persistent vector database

Cosine similarity-based retrieval

🔹 Features

Converts articles into high-dimensional embedding vectors (3072-dim)

Stores embeddings in a persistent ChromaDB collection

Supports similarity search using custom query embeddings

Handles batch embedding for scalability

Fully persistent storage using Google Drive or local disk

🔹 Architecture

Text → Gemini Embedding Model → Vector Representation → ChromaDB → Similarity Search

🔹 How It Works

Load article dataset

Generate embeddings using Gemini

Store embeddings in ChromaDB

Embed user query

Retrieve top-K similar documents
