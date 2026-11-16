# Myntra FitConfidence
### Product Management Case Study | Men's T-Shirts

> **Status: Product discovery and planning.** This repository documents a proposed product concept. The MVP, recommendation engine, CV estimation, and GenAI fit simulation are not yet implemented.

Myntra FitConfidence is a proposed experience to help online shoppers choose a Men's T-Shirt size with more confidence through measurement-aware size recommendations, product dimensions, fit preference, purchase-history signals (with permission), and an optional AI-generated visual fit simulation.

## Problem
Online apparel shoppers cannot physically assess garment fit before purchase. Brand/style sizing variation, difficult size charts, and insufficient contextual fit information can make size selection uncertain.

## Proposed solution
- Body profile: height, chest measurement, optional weight, fit preference
- Product-specific garment measurements and size-chart matching
- Transparent recommendation rationale
- Estimated length/fit cues when data supports them
- Optional authorized purchase-history personalization
- Future: CV fit estimation and GenAI visual fit simulation, clearly labeled as estimates

## Repository guide
| File | Purpose |
|---|---|
| `docs/01_problem_statement.md` | Problem framing, target user, goals/non-goals |
| `docs/02_research_plan_and_method.md` | Research methodology and limitations |
| `docs/03_survey_findings.md` | Summary of Google Forms survey findings |
| `docs/04_external_research_and_references.md` | External evidence and cited references |
| `docs/05_product_requirements_document.md` | PRD v2.0 |
| `docs/06_product_prioritization.md` | Impact/effort, MVP vs future scope |
| `docs/07_product_backlog.md` | Epics, stories, acceptance criteria |
| `docs/08_user_journey_and_flows.md` | Journey and flow |
| `docs/09_technical_feasibility.md` | Proposed architecture, feasibility, dependencies |
| `docs/10_figma_screen_plan.md` | Screen inventory and design plan |
| `docs/11_execution_roadmap.md` | Proposed timeline and Definition of Done |
| `docs/12_metrics_and_experiment_plan.md` | KPI definitions and validation approach |
| `docs/13_risks_assumptions_open_questions.md` | Risks, assumptions, open questions |
| `docs/14_portfolio_case_study.md` | HR-friendly case-study narrative |
| `data/survey_data_dictionary.md` | Survey data handling notes |
| `references.md` | Short bibliography |
| `LICENSE` | MIT license for original documentation (review before public use) |

## Research snapshot
The survey contains 16 submissions, 14 of whom indicated an online T-Shirt purchase within the last six months and had eligible responses for the core analysis. The small convenience sample is exploratory and not representative. Read `docs/03_survey_findings.md` for exact denominator and limitations.

## Product principles
1. Data-backed recommendations; do not invent missing product measurements.
2. BMI is supplementary and must not be the primary apparel sizing signal.
3. A generated image is a simulation, not a promise of real-world fit.
4. Use purchase history and body profile data only with appropriate permission, minimization, and user control.
5. Treat reduction in returns as a hypothesis to test—not a guaranteed outcome.

## How to present this project
Describe it as a **Product Management case study / proposed product concept**. Do not claim Myntra affiliation, production deployment, validated return reduction, or implementation of AI components unless those are actually achieved.

## Author
Product case study by Randhir Kumar. Replace/add portfolio and LinkedIn links as desired.
