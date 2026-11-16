# LLM Answer Reliability Checker

> Status: In development (started November 2026)

## Overview
Large language models can produce answers that sound confident but are not supported by their source material. This project explores a simple way to detect that problem.

The tool answers questions from a set of documents using retrieval-augmented generation (RAG), then checks each answer against the retrieved source text and flags answers that are not supported.

## Planned features
- Upload a small set of documents (PDF or text)
- Split documents into chunks and store embeddings for retrieval
- Answer user questions using the most relevant chunks
- Verify each answer against its sources and label it as Supported, Partially supported or Unsupported
- Show the source passages used for each answer
- Track simple reliability statistics across a set of test questions

## Planned tech stack
- TypeScript, Node.js, Express.js
- OpenAI / Claude APIs (generation and verification)
- PostgreSQL with pgvector (via Supabase) for embeddings
- React for a simple interface

## Goals
- Understand how retrieval quality affects answer reliability
- Compare different verification approaches for LLM outputs
- Build a small evaluation set to measure how often answers are unsupported

## Roadmap
- [ ] Document ingestion and chunking
- [ ] Embedding storage and retrieval
- [ ] Question answering with sources
- [ ] Answer verification step
- [ ] Reliability statistics and evaluation
