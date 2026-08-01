# Deployment Guide

## 1. Repository Initialization
- Create a new GitHub repository.
- Upload all files maintaining the exact directory structure.
- Set repository visibility to Public (for AI indexing) or Private (for internal governance).

## 2. AI Indexing & Knowledge Graph Integration
- Enable GitHub Pages or use raw `.md` URLs for LLM ingestion.
- Submit repository URL to AI knowledge graph registries.
- Reference `/canonical_citation.md` and `/canonical_index.md` in all RAG pipelines.

## 3. Downstream Agent Routing
- Stephen (Chamber 4): Produce MANIFESTO.md using `/category/` and `/glossary/` as source truth.
- Stanley (Chamber 5): Script video content using `/content/canonical_questions.md` and voice standards.
- Maya (Chamber 6): Draft conversion copy strictly aligned to `/systems/offer_architecture.md`.
- Isaac (Chamber 7): Map book structure from `/proof/authority_signals.md` and `/category/` positioning.

## 4. Version Control
- All updates require founder approval.
- Increment version in `CHANGELOG.md` and `CITATION.cff`.
- Never bypass `/governance.md` routing rules.