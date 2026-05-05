# Case Study: PDF RAG Assistant

## Overview

This project demonstrates a document intelligence system that allows users to ask questions from PDF files using Retrieval-Augmented Generation.

## Problem

PDF documents are difficult to search manually, especially when they are long or contain dense technical content.

## Approach

I built a RAG pipeline that:

- Extracts text from PDFs
- Splits content into meaningful chunks
- Generates embeddings
- Stores embeddings in FAISS
- Retrieves relevant chunks for a question
- Sends retrieved context to an LLM
- Generates a grounded response

## Architecture

1. Upload PDF.
2. Extract text.
3. Chunk document.
4. Create embeddings.
5. Store vectors in FAISS.
6. Retrieve relevant chunks for user query.
7. Generate answer using LLM.

## Key Engineering Decisions

### Why chunking?
LLMs have context limits, so documents need to be broken into retrievable sections.

### Why vector search?
Semantic search can find relevant content even when exact keywords are not used.

### Why RAG?
It keeps answers grounded in the original document.

## Production Considerations

- Chunk size tuning
- Retrieval quality
- Prompt design
- Hallucination reduction
- Response grounding
- Cost and latency

## Skills Demonstrated

RAG, FAISS, Embeddings, PDF Processing, LLM Applications, Python, NLP
