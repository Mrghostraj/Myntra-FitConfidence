# Myntra FitConfidence
### Product Management Case Study | Men's T-Shirts

> **Status: Product Discovery & Planning.** This repository documents an independent Product Management case study and proposed product concept. The MVP, recommendation engine, CV estimation, and GenAI fit simulation are not yet implemented[cite: 1].

Myntra FitConfidence is a proposed fit-guidance experience designed to help online shoppers choose a Men's T-Shirt size with greater confidence—combining measurement-aware size recommendations, garment-specific dimensions, fit preference, permissioned purchase-history signals, and an optional, clearly labeled AI visual fit simulation[cite: 1].

---

## Problem
Online apparel shoppers cannot physically assess garment fit prior to purchase[cite: 1]. Inconsistent sizing across brands and styles, dense size charts, and static model photography leave shoppers uncertain about how a T-Shirt will actually fit their body—driving hesitation, cart abandonment, and size-related returns[cite: 1, 18].

## Proposed Solution
* **Body Profile & Fit Preference:** Lightweight capture of height, chest measurement, optional weight, and preferred fit (`Slim`, `Regular`, or `Relaxed`)[cite: 1, 4].
* **Garment-Grounded Size Matching:** Deterministic size recommendations anchored in SKU-specific product dimensions and documented ease rules[cite: 1, 4, 5].
* **Transparent Recommendation Rationale:** Plain-language explanations detailing *why* a size is recommended (and clear guidance when a shopper falls between sizes)[cite: 1, 4].
* **Contextual Fit & Length Cues:** Estimated body/garment length indicators where reliable product dimension data exists[cite: 1, 4].
* **Permissioned Personalization:** Optional integration of prior purchase and return signals with explicit user consent and deletion controls[cite: 1, 5, 6].
* **Future Scope — Visual Fit Simulation:** Optional CV/GenAI visual preview clearly labeled as an approximate simulation rather than a guaranteed fit[cite: 1, 6].

---

## Research Snapshot
An exploratory 18-question Google Forms survey collected **16 submissions**, of which **$n = 14$ respondents** purchased T-Shirts online within the past 6 months and qualified for core analysis[cite: 1, 19, 20]. Within this directional convenience sample:
* **85.7% (12/14)** have received an online T-Shirt that did not fit as expected (*frequently* or *sometimes*)[cite: 20].
* **78.6% (11/14)** have returned or exchanged a T-Shirt *multiple times* due to size or fit issues[cite: 20].
* **78.6% (11/14)** cited **different sizing across brands** as their single biggest size-selection challenge[cite: 20].
* **85.7% (12/14)** selected **personalized size recommendations** as helpful, and **85.7% (12/14)** rated an explanation of *why* a size is recommended as `4` or `5` out of 5[cite: 20].
* **78.6% (11/14)** were comfortable providing **chest measurement**, and **71.4% (10/14)** were comfortable sharing **height** and **fit preference**[cite: 20].

> **Methodological Caveat:** This is a small, non-probability convenience sample and is not statistically representative of all online apparel shoppers[cite: 1, 19]. See `docs/02_research_plan_and_method.md` and `docs/03_survey_findings.md` for full methodology, denominators, and limitations[cite: 1].

---

## Repository Guide
| File | Purpose |
|---|---|
| `docs/01_problem_statement.md` | Problem framing, target segment, JTBD, goals & non-goals[cite: 1] |
| `docs/02_research_plan_and_method.md` | Survey design, sampling method, limitations & follow-up research[cite: 1, 19] |
| `docs/03_survey_findings.md` | Quantitative & qualitative synthesis of Google Forms survey ($n = 14$)[cite: 1, 20] |
| `docs/04_external_research_and_references.md` | Industry literature context and cited evidence[cite: 1, 2] |
| `docs/05_product_requirements_document.md` | Product Requirements Document (PRD v2.0)[cite: 1] |
| `docs/06_product_prioritization.md` | Impact vs. effort matrix and MVP vs. future scoping[cite: 1] |
| `docs/07_product_backlog.md` | Epics, user stories, and acceptance criteria[cite: 1] |
| `docs/08_user_journey_and_flows.md` | End-to-end user journey, Mermaid flow, and edge cases[cite: 1, 4] |
| `docs/09_technical_feasibility.md` | Proposed system architecture, feasibility, and data governance |
| `docs/10_figma_screen_plan.md` | Screen inventory, release phasing, and UX requirements[cite: 1, 6] |
| `docs/11_execution_roadmap.md` | 4-week prototype plan and MVP Definition of Done[cite: 1, 7] |
| `docs/12_metrics_and_experiment_plan.md` | North-star candidate, funnel KPIs, guardrails, and A/B test design[cite: 1, 8] |
| `docs/13_risks_assumptions_open_questions.md` | Risk register, core assumptions, and open product questions[cite: 1, 9] |
| `docs/14_portfolio_case_study.md` | Recruiter/HR-ready case-study summary[cite: 1, 10] |
| `data/survey_data_dictionary.md` | Survey schema, privacy rules, and denominator conventions[cite: 1, 3] |
| `references.md` | Academic and UX research bibliography[cite: 1, 2] |
| `LICENSE` | MIT license for original documentation[cite: 1] |

---

## Product Principles
1. **Evidence over fabrication:** Ground recommendations strictly in verified product measurements; fall back gracefully when SKU dimensions are missing[cite: 1, 4].
2. **Garment-first modeling:** Use chest and garment dimensions as primary sizing signals; treat BMI strictly as a supplementary metric[cite: 1, 5].
3. **Honest AI boundaries:** Label any generated fit visual as an approximate simulation, never a photographic guarantee[cite: 1, 6].
4. **Privacy by design:** Minimize personal data collection, gate purchase history behind explicit opt-in consent, and provide user edit/delete controls.
5. **Hypothesis-driven impact:** Treat conversion lift and return reduction as hypotheses to validate through testing—never pre-claimed outcomes

## Presentation Disclaimer
Please reference this repository as an **independent Product Management case study / proposed product concept**[cite: 1, 10]. Do not claim official Myntra affiliation, production deployment, validated return-rate reductions, or live AI implementation[cite: 1].

## Author
**Randhir Kumar** — Product Management Case Study
