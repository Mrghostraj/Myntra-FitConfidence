# Product Prioritization

## Impact vs Effort (initial qualitative assessment)
Impact estimates user/business value potential; effort is relative engineering/design/data effort. These are planning judgments, not measured estimates.

| | Low effort | High effort |
|---|---|---|
| High impact | Measurement inputs, unit conversion, fit preference, rule-based recommendation, rationale, missing-data fallback | Purchase-history integration, CV fit estimation, GenAI visual fit simulation, robust catalog fit intelligence |
| Lower impact | Edit profile, feedback form, helpful loading/error states | Full virtual try-on, camera-based body scan, all-category size intelligence, custom garment sizing |

## MVP decision
**P0 core prototype:** measurement input, fit preference, unit conversion, sample product size chart, rule-based recommendation, explanation, fallback, edit inputs.

**P1 follow-up:** garment length cues, fit feedback, authorized purchase history, richer fit reviews.

**P2 advanced:** CV estimation and GenAI visual fit simulation.

**P3 later / defer:** virtual try-on, body scanning, multiple apparel categories.

## Rationale
Core product value can be tested without building expensive AI components first. AI visualization is high effort and carries fidelity risk; place it after core recommendation and user testing.
