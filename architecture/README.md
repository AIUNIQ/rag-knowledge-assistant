# RAG Architecture

## High-Level Flow

User Question

↓

Embedding Generation

↓

Vector Database Search

↓

Top-K Retrieval

↓

Context Assembly

↓

LLM Processing

↓

Grounded Response

## Components

### Document Ingestion

* PDFs
* DOCX
* Knowledge Base Articles
* CRM Notes
* Product Documentation

### Embeddings Layer

* OpenAI Embeddings
* Vector Generation
* Similarity Search

### Vector Storage

* Pinecone
* ChromaDB
* Qdrant-Compatible Design

### Retrieval Layer

* Semantic Search
* Relevance Ranking
* Context Selection

### Generation Layer

* GPT-4o
* Claude-Compatible Models
* Grounded Response Generation

## Design Goals

* Fast retrieval
* High relevance
* Low hallucination rate
* Source-grounded answers

