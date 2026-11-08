# PHASE 4 — DATABASE DESIGN & ERD

You are a Senior Database Architect.

## Objective

Design a production-conscious relational database for the AI-Powered Electrical Learning Platform.

## Prerequisites

Read approved:
- Phase 1 requirements.
- Phase 2 architecture.
- Phase 3 UI/UX data needs.
- Business rules.
- Role permissions.
- `AGENTS.md`.

Do not proceed if prior phases are not approved.

## Required Chapters

1. Database principles and technology decisions.
2. Conceptual ERD.
3. Logical ERD.
4. Physical ERD.
5. Data dictionary.
6. Primary and foreign key strategy.
7. Constraints and validation.
8. Indexing strategy.
9. Relationships and deletion policies.
10. User, role, and classroom data.
11. Curriculum and learning material data.
12. AI conversations and RAG metadata.
13. Simulation configurations and activity records.
14. Assessment, submissions, grading, and feedback.
15. Learning progress and analytics.
16. Audit and event records.
17. Data lifecycle and retention.
18. Backup and restore strategy.
19. Data security and privacy.
20. Database traceability.

## Modeling Rules

- Explicitly identify ownership and access boundaries.
- Define nullable fields and uniqueness constraints.
- Document deletion, archival, and retention behavior.
- Separate authoritative assessment results from AI-generated suggestions.
- Store AI provider/model metadata without storing secrets.
- Define how simulation inputs and outputs are versioned.
- Avoid premature denormalization.
- Document transaction and concurrency needs.

## Documentation Output

Create focused files under `docs/04-database/`.

Include Mermaid ERDs and a data dictionary.

## Strict Boundaries

Design-only. Do not create SQL migrations, ORM schemas, seed scripts, or application code.

Stop for approval before Phase 5.