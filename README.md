# Enterprise AI Knowledge & Workflow Copilot

An AI-powered enterprise knowledge assistant that retrieves information from company documents and generates context-grounded answers with source citations.

**Status:** In Progress

## Overview

This project aims to build a full-stack AI application that enables users to upload enterprise documents, ask questions about their contents, and receive answers supported by relevant document passages.

The system uses Retrieval-Augmented Generation (RAG) to retrieve relevant information before passing context to a Large Language Model (LLM).

## Technology Stack

- **Frontend:** React, TypeScript
- **Backend:** Java 21, Spring Boot
- **AI Service:** Python, FastAPI
- **Database:** PostgreSQL, pgvector
- **AI:** LLM integration, embeddings, semantic search, RAG
- **Deployment:** Docker, CI/CD

## Planned Features

- Document upload and text extraction
- Text chunking and embedding generation
- Vector storage and similarity search
- RAG-based question answering
- Answers with source citations
- REST APIs and full-stack integration
- Authentication and role-based access control
- RAG evaluation and retrieval-quality measurement
- Containerization and deployment

## Project Structure

```text
enterprise-ai-copilot/
├── ai_service/
├── backend/
├── frontend/
├── docs/
├── README.md
└── .gitignore
```

## Development Roadmap

1. **Phase 1:** Build the working RAG pipeline.
2. **Phase 2:** Integrate the full-stack application.
3. **Phase 3:** Improve retrieval quality, evaluation, security, and observability.
4. **Phase 4:** Add testing, containerization, CI/CD, and deployment.

## Current Progress

PostgreSQL 16 is configured with pgvector 0.8.6. Implementation of the RAG pipeline is the next milestone.

## Engineering Goals

- Understand the complete RAG pipeline.
- Build reliable APIs and database integrations.
- Evaluate retrieval and answer quality.
- Apply software engineering and security best practices.
- Document architectural decisions and implementation trade-offs.