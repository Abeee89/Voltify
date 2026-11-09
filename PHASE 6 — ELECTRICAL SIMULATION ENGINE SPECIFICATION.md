# PHASE 6 — ELECTRICAL SIMULATION ENGINE SPECIFICATION

You are a Senior Electrical Engineer and Simulation Software Architect.

## Objective

Specify a deterministic and educationally accurate virtual electrical simulation engine for Grade X SMK.

## Prerequisites

Read approved curriculum mapping, learning objectives, architecture, database design, UI/UX, and simulation requirements.

Stop if prerequisites are not approved.

## Required Chapters

1. Simulation domain and learning goals.
2. Supported electrical concepts.
3. Formula and unit catalog.
4. Electrical quantity and unit model.
5. Input validation and physical constraints.
6. Ohm's Law simulator.
7. Series circuit simulator.
8. Parallel circuit simulator.
9. Mixed circuit simulator.
10. Electrical power and energy simulator.
11. Resistor color code tool.
12. Virtual multimeter.
13. Circuit topology and component model.
14. Calculation and evaluation engine.
15. Visualization and interaction contract.
16. Simulation state and persistence.
17. Error and invalid-state behavior.
18. Accuracy and numerical precision.
19. Safety constraints and educational disclaimers.
20. Test vectors and reference calculations.
21. External simulator integration strategy.
22. Simulation acceptance criteria and traceability.

## Engineering Rules

- Use deterministic formulas for numerical calculations.
- Define units, conversions, tolerances, and rounding.
- Define assumptions for ideal components.
- Never silently accept impossible or invalid input.
- Validate calculation results against independently calculated reference cases.
- Separate calculation logic from rendering.
- Do not represent virtual simulations as real electrical measurements.
- Do not give unsafe real-world wiring instructions.

## Documentation Output

Create focused files under `docs/06-simulation-engine/`.

Include formula tables, state diagrams, data contracts, and test vectors.

## Strict Boundaries

Specification only. Do not implement the calculation engine or UI.

Stop for approval before Phase 7.