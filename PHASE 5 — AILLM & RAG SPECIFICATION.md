# PHASE 5 — AI/LLM & RAG SPECIFICATION

You are a Senior AI Engineer and LLM Architect.

## Objective

Design the AI subsystem for the electrical learning platform, with multi-provider support and curriculum-grounded tutoring.

## Prerequisites

Read approved:
- Product and AI requirements.
- System architecture.
- Database design.
- Curriculum mapping.
- Role permissions.
- Security and privacy rules.
- `AGENTS.md`.

Stop if prerequisites are not approved.

## Required Chapters

1. AI subsystem overview.
2. Provider abstraction and adapter contracts.
3. Provider capability matrix.
4. Model selection and routing policy.
5. Streaming and structured output.
6. AI Tutor conversation lifecycle.
7. RAG architecture.
8. Knowledge source governance.
9. Document ingestion and parsing.
10. Chunking and metadata strategy.
11. Embedding and vector retrieval.
12. Hybrid retrieval and reranking strategy.
13. Context assembly and citation behavior.
14. Prompt architecture and prompt versioning.
15. Electrical-domain guardrails.
16. Student, teacher, and admin AI permissions.
17. AI-generated assessment support.
18. Teacher review and approval workflow.
19. Token quotas, cost monitoring, and rate limits.
20. Provider failure and fallback handling.
21. Privacy, retention, and audit.
22. AI evaluation and regression dataset.
23. AI acceptance criteria and traceability.

## Critical Rules

- AI must distinguish sourced facts from uncertainty.
- AI responses about course content must prioritize approved learning materials.
- AI must not fabricate citations.
- AI must not be the authoritative engine for electrical calculations.
- AI-generated grading must not silently replace teacher judgment.
- Define safeguards for unsafe electrical advice.
- Document what happens when no relevant RAG source is found.
- Keep provider-specific SDKs behind adapters.

## Documentation Output

Create focused files under `docs/05-ai-llm-rag/`.

Include sequence diagrams, contracts, prompt specifications, evaluation criteria, and operational limits.

## Strict Boundaries

Do not implement chatbot UI, provider SDK integrations, embeddings, vector database, or API routes.

Stop for approval before Phase 6.