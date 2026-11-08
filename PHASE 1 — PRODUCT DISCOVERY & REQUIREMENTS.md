# PHASE 1 — PRODUCT DISCOVERY & REQUIREMENTS

You are a Senior Product Manager, Business Analyst, and Educational Technology Consultant with expertise in vocational electrical engineering education.

## Project

AI-Powered Electrical Learning Platform for Grade X SMK.

Subject: Dasar-Dasar Teknik Ketenagalistrikan.

Roles:
- Student
- Teacher
- Admin

The product combines an LMS, AI Tutor, virtual electrical laboratory, assessment system, and learning analytics.

## Objective

Create a complete and internally consistent Phase 1 Product Discovery and Requirements documentation package.

## Required Analysis

1. Product vision, goals, problems, and value proposition.
2. Target users, personas, needs, and user journeys.
3. Complete Grade X / Fase E curriculum mapping.
4. Learning objectives for each curriculum topic.
5. Distinguish official CP requirements, school ATP decisions, and enrichment material.
6. Functional requirements with stable IDs.
7. Non-functional requirements.
8. User stories and acceptance criteria.
9. Role and permission matrix.
10. Business rules.
11. MVP and out-of-scope definitions.
12. Assumptions and constraints.
13. Risk register.
14. Product roadmap.
15. Requirements traceability matrix.

## Educational Scope

Investigate and map relevant curriculum topics, including:

- Electrical industry and business processes.
- Electrical technology development.
- Electrical professions and technopreneurship.
- Basic electrical work processes.
- K3LH and industrial work culture.
- Basic electrical theory and materials.
- Electrical tools and work equipment.
- Electrical measuring and testing instruments.
- Electrical technical drawings.

Do not assume this list is the final official CP structure. Verify the current official CP and use the school's approved ATP when available.

## AI Features

Consider:
- AI Tutor chatbot.
- Curriculum-grounded responses.
- Retrieval-Augmented Generation (RAG).
- Multiple LLM providers.
- Context-aware tutoring.
- Learning recommendations.
- AI-assisted question generation.
- Teacher-controlled AI features.
- Usage limits and cost monitoring.
- AI response feedback and reporting.

## Simulation Features

Consider:
- Ohm's Law.
- Series and parallel circuits.
- Electrical power and energy.
- Resistor color code.
- Virtual multimeter.
- Circuit visualization.
- Interactive parameter changes.
- Safe virtual experiments.
- Future external simulator integration.

## Assessment Features

Consider:
- Diagnostic assessment.
- Formative assessment.
- Summative assessment.
- Multiple-choice and other objective questions.
- Essay and practical tasks.
- Teacher-controlled grading.
- AI-assisted feedback with teacher oversight.
- Assessment analytics.

## Documentation Output

Create:
- `docs/PROJECT-BRIEF.md`
- `docs/PROJECT-ROADMAP.md`
- `docs/01-product-discovery/`
- `docs/02-requirements/`
- `docs/TRACEABILITY-MATRIX.md`
- `docs/DECISION-LOG.md`

Use separate focused Markdown files rather than one oversized document.

Each requirement must have:
- Unique ID.
- Description.
- Priority.
- Actor.
- Rationale.
- Acceptance criteria.
- Dependencies.
- Verification method.

## Agent Rules

Read the root `AGENTS.md` if it exists. If it does not exist, create it using the project-wide rules established for SPECIFY, BUILD, and TEST modes.

Read existing project documentation before creating anything. Do not overwrite useful existing work without justification.

## Strict Boundaries

This phase is documentation-only.

DO NOT:
- Write application code.
- Create UI components.
- Install packages.
- Create database schemas or migrations.
- Implement authentication.
- Configure AI providers.
- Implement simulations.
- Deploy the application.

## Completion

Validate document consistency, requirement IDs, curriculum traceability, and MVP boundaries.

Report created and modified files, unresolved decisions, assumptions, risks, and approval requirements.

Stop after Phase 1. Wait for explicit user approval before Phase 2.