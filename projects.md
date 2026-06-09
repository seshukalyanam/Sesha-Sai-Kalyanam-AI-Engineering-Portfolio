# Project Portfolio

This document summarizes my strongest portfolio projects and the value each one demonstrates.

---

## Multi-Tenant Isolated RAG System

**Problem**  
Enterprise customers need AI assistants that answer from their own data without leaking information across tenants.

**Solution**  
Designed a multi-tenant RAG system where each customer has a separate index and retrieval path.

**Technical Highlights**
- Azure OpenAI for answer generation
- Azure AI Search for retrieval
- Customer-specific indexes
- Secure data isolation
- Chunking and embeddings
- Streamlit-based interface

**Business Value**
- Enables secure enterprise knowledge search
- Reduces manual document lookup
- Supports customer-specific AI assistants

---

## Agentic AI System

**Problem**  
Traditional chatbots struggle with multi-step tasks, tool usage, and dynamic workflows.

**Solution**  
Built an agentic AI system with modular agents, orchestration logic, retrieval, and tool calling.

**Technical Highlights**
- LangGraph and LangChain orchestration
- LLM-based routing
- Tool usage
- FAISS retrieval
- Streamlit UI
- Modular architecture

**Business Value**
- Supports complex reasoning workflows
- Enables task delegation
- Demonstrates real-world agentic AI design

---

## PDF RAG Assistant

**Problem**  
Users need to ask questions from large PDF documents without manually searching through pages.

**Solution**  
Built an LLM-powered PDF RAG assistant that retrieves relevant chunks and generates grounded answers.

**Technical Highlights**
- PDF parsing
- Chunking
- Embeddings
- FAISS vector search
- Context-aware answer generation

**Business Value**
- Automates document search
- Improves knowledge retrieval
- Useful for legal, healthcare, HR, and enterprise document workflows

---

## AI-Powered Card Grading Engine

**Problem**  
Trading card grading is manual, subjective, and time-consuming.

**Solution**  
Built a computer vision model that analyzes card images and predicts condition grades.

**Technical Highlights**
- Image preprocessing
- OpenCV feature extraction
- TensorFlow model training
- Streamlit app
- Real-time prediction workflow

**Business Value**
- Demonstrates applied computer vision
- Shows end-to-end ML workflow
- Useful for collectibles and visual quality inspection

---

## Stance Detection on Diversity Hiring

**Problem**  
Organizations need to analyze opinions and stance in text data.

**Solution**  
Built an NLP classification pipeline to detect stance in diversity hiring-related content.

**Technical Highlights**
- Text preprocessing
- Transformer-based NLP
- Classification modeling
- Evaluation metrics

**Business Value**
- Supports sentiment and stance analysis
- Useful for HR analytics, social listening, and policy research


---

## SIA: Voice-Interactive Multi-Agent AI Platform

**Problem**  
Organizations need AI assistants capable of handling real-time voice conversations, domain-specific expertise, and complex multi-step reasoning without requiring users to interact through traditional chat interfaces.

**Solution**  
Developed SIA (Smart Intelligent Assistant), a low-latency, voice-interactive multi-agent AI platform that enables users to communicate naturally through voice while leveraging a network of specialized AI agents. The system streams audio in real time, performs transcription, routes requests to the appropriate expert agents, and generates contextual responses with automated conversation summaries.

**Technical Highlights**
- Built using Google ADK and Gemini Live APIs
- Implemented WebSocket-based bidirectional streaming for low-latency communication
- Orchestrated approximately 40 specialized subject-matter expert agents
- Dynamic agent routing and delegation based on user intent
- Real-time speech-to-text and text-to-speech workflows
- Context management and memory across conversations
- Automated meeting and conversation summarization
- Multi-agent response aggregation and reasoning
- Scalable agent orchestration architecture
- Latency optimization for near real-time interactions

**Business Value**
- Enables natural voice-first interactions with AI systems
- Reduces response times through specialized agent delegation
- Improves knowledge accessibility across multiple domains
- Supports enterprise-scale AI assistant deployments
- Demonstrates advanced agentic AI architecture and orchestration patterns

---

## Etypist Courtroom Transcription Intelligence Platform

**Problem**  
Courtroom transcription requires extremely high accuracy, speaker attribution, legal terminology recognition, and reliable handling of diverse accents and speaking styles. Generic speech-to-text systems often fail to meet legal documentation standards.

**Solution**  
Enhanced an existing transcription platform for Etypist by integrating AI-powered speech recognition capabilities using AWS Transcribe and advanced customization features. The solution improved transcription quality, speaker separation, and domain-specific terminology recognition for courtroom proceedings.

**Technical Highlights**
- Integrated AWS Transcribe into existing enterprise application workflows
- Developed custom vocabularies for legal and courtroom terminology
- Implemented custom language models to improve recognition accuracy
- Configured speaker diarization for multi-speaker courtroom sessions
- Automated transcript generation and post-processing workflows
- Built transcription quality validation and review pipelines
- Improved handling of legal jargon, names, and case-specific terminology
- Optimized transcription latency and processing efficiency
- Integrated cloud-native processing and storage workflows
- Designed scalable architecture for high-volume transcription requests

**Business Value**
- Improved courtroom transcription accuracy
- Reduced manual transcription effort and review cycles
- Enhanced speaker identification and conversation tracking
- Increased reliability for legal documentation workflows
- Demonstrated practical application of enterprise speech AI technologies
