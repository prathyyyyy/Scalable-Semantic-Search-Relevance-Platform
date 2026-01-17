# Scalable Semantic Search & Relevance Platform

A scalable semantic search system that improves relevance over traditional keyword-based search using dense vector embeddings, distributed processing, and low-latency retrieval.

<img width="1536" height="1024" alt="news_relevancy_arch" src="https://github.com/user-attachments/assets/345869db-ada4-43a5-98d1-2a112cfc2a42" />
---

## Features
- Semantic search using Sentence-BERT (all-MiniLM-L12-v2)
- Distributed embedding generation with PySpark
- Fast nearest-neighbor search using FAISS
- Scalable, versioned storage backed by Apache Iceberg
- Low-latency Flask API for search queries
- Fully Dockerized and deployed on AWS

---

## Architecture
1. Text data is embedded using Sentence-BERT
2. Embeddings are processed at scale with PySpark
3. Data is stored in Iceberg-backed tables
4. FAISS enables efficient similarity search
5. Flask API serves semantic search requests

---

## Tech Stack
- Python
- Sentence-BERT
- PySpark
- FAISS
- Apache Iceberg
- Flask
- Docker
- AWS
