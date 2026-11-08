# PHASE 2 — SYSTEM ARCHITECTURE & TECHNICAL DESIGN

You are a Senior Software Architect and Technical Lead.

## Objective

Create the complete technical architecture specification for the AI-Powered Electrical Learning Platform.

## Prerequisites

Read only the relevant approved documents from:
- `docs/PROJECT-BRIEF.md`
- `docs/PROJECT-ROADMAP.md`
- `docs/01-product-discovery/`
- `docs/02-requirements/`
- `docs/TRACEABILITY-MATRIX.md`
- `docs/DECISION-LOG.md`
- `AGENTS.md`

Verify that Phase 1 has been approved. If not, stop.

## Required Chapters

1. System context and architecture overview.
2. Architecture principles and quality attributes.
3. Technology evaluation and ADRs.
4. Frontend and backend architecture.
5. Module boundaries and dependency rules.
6. Authentication and authorization architecture.
7. API architecture and error conventions.
8. File and document storage architecture.
9. AI provider abstraction architecture.
10. RAG and vector search integration boundaries.
11. Simulation engine architecture.
12. Assessment and grading architecture.
13. Background jobs and notification architecture.
14. Security, privacy, and audit architecture.
15. Observability and logging.
16. Cloud deployment architecture.
17. Environment and configuration strategy.
18. Scalability, performance, and resilience.
19. Architecture decision records.
20. Architecture traceability.

## Multi-Provider AI Requirements

Design a provider-independent adapter architecture. Evaluate provider capabilities, structured output, streaming, embeddings, rate limits, pricing, privacy, and fallback behavior.

Do not bind the application domain directly to one provider's SDK.

## Simulation Requirements

The simulation calculation engine must be deterministic, independently testable, and separated from the LLM layer.

## Security Requirements

Define server-side authorization, secure session handling, secret management, file access controls, rate limiting, audit logs, and student-data protection.

## Documentation Output

Create `docs/02-architecture/` with focused Markdown chapters and ADR files.

Update:
- `docs/DECISION-LOG.md`
- `docs/TRACEABILITY-MATRIX.md`
- `docs/PROJECT-ROADMAP.md`

## Strict Boundaries

Documentation-only. Do not create application source code, install dependencies, create migrations, configure cloud services, or deploy.

For every major technology choice, document alternatives, trade-offs, rationale, and consequences.

Stop and request approval before Phase 3.