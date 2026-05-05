# Case Study: Multi-Tenant Isolated RAG System

## Overview

This project demonstrates an enterprise-style Retrieval-Augmented Generation system where each customer has isolated data access through separate indexes.

## Problem

In enterprise AI systems, data leakage between customers is a major risk. A generic RAG system can accidentally retrieve information from the wrong customer if tenant isolation is not designed properly.

## Approach

I designed the system so each customer has:

- Separate document storage
- Separate vector/search index
- Tenant-specific retrieval logic
- Controlled query routing
- Isolated answer generation context

## Architecture

1. User selects customer or tenant.
2. Query is routed only to that tenant’s index.
3. Relevant chunks are retrieved.
4. Retrieved context is passed to the LLM.
5. LLM generates a grounded answer only from that tenant’s data.

## Key Engineering Decisions

### Why separate indexes?
To reduce the risk of cross-customer data leakage and make access control easier to reason about.

### Why RAG instead of fine-tuning?
RAG allows customer documents to be updated without retraining a model.

### Why Azure AI Search?
It supports enterprise retrieval, filtering, and scalable indexing patterns.

## Production Considerations

- Tenant isolation
- Retrieval accuracy
- Hallucination reduction
- Latency optimization
- Token cost control
- Monitoring and logging
- Secure access control

## Skills Demonstrated

Azure OpenAI, Azure AI Search, RAG, Vector Search, LLM Applications, System Design, Secure AI Architecture
