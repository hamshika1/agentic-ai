# agentic-ai
# AI & Agentic Systems Portfolio

## Overview

This repository contains a collection of projects focused on Agentic AI, Retrieval-Augmented Generation (RAG), Vector Databases, Multi-Agent Systems, and LLM Observability.

The projects demonstrate practical implementation of modern AI development using LangChain, LangGraph, Gemini, Qdrant, and LangSmith.

---

## Projects Included

### 1. Conversational AI Agent
📄 File: `agent_1(2).ipynb`

A conversational AI assistant built using LangChain and Gemini that supports memory, tool calling, and interactive chat sessions.

#### Features
- Gemini 2.5 Flash integration
- LangChain Agent architecture
- Tool calling support
- Conversation memory
- Multi-turn interactions
- Session management using UUID

#### Technologies
- Python
- LangChain
- LangGraph
- Gemini API

---

### 2. Vector Database Integration with Qdrant
📄 File: `task4.ipynb`

A document embedding and storage system that converts uploaded documents into vector embeddings and stores them in Qdrant for semantic search.

#### Features
- PDF processing
- Text extraction
- Embedding generation
- Vector storage
- Semantic search foundation
- RAG-ready architecture

#### Technologies
- Python
- Qdrant
- Sentence Transformers
- PyPDF

---

### 3. Multi-Agent Interview Preparation System
📄 File: `langgraph.ipynb`

An intelligent interview preparation platform built using LangGraph and multiple specialized AI agents.

#### Agents Included

##### JD Analyst Agent
Analyzes job descriptions and extracts:
- Required skills
- Responsibilities
- Keywords
- Role expectations

##### Experience Mapper Agent
Matches candidate experience against job requirements.

##### Behavioral Interview Agent
Generates HR and behavioral interview questions.

##### Technical Interview Agent
Creates technical questions based on the role.

##### Evaluation Agent
Produces a final readiness report.

#### Workflow

```text
Job Description
       ↓
JD Analyst
       ↓
Experience Mapper
       ↓
Behavioral Interviewer
       ↓
Technical Interviewer
       ↓
Evaluation Agent
       ↓
Final Interview Report
