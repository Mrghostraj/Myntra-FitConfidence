# Myntra FitConfidence
### Product Management Case Study | Men's T-Shirts

![Status](https://img.shields.io/badge/Stage-Product_Discovery_%26_Planning-blue)
![Category](https://img.shields.io/badge/Category-Men's_T--Shirts-ff3f6c)
![Sample](https://img.shields.io/badge/User_Survey-n%3D14_Active_Buyers-0d9488)
![Scope](https://img.shields.io/badge/Core_MVP-Explainable_Rule_Engine-slate)

> **Status: Product Discovery & Planning.** This repository documents an independent Product Management case study and proposed product concept. The MVP, recommendation engine, CV estimation, and GenAI fit simulation are not yet implemented.

![Myntra FitConfidence Concept UI](assets/fitconfidence_ui_concept.png)
*Conceptual mobile flow: PDP Entry → Body Profile & Fit Preference → Explainable Size Recommendation & Optional AI Fit Simulation.*

Myntra FitConfidence is a proposed fit-guidance experience designed to help online shoppers choose a Men's T-Shirt size with greater confidence—combining measurement-aware size recommendations, garment-specific dimensions, fit preference, permissioned purchase-history signals, and an optional, clearly labeled AI visual fit simulation.

---

## Problem
Online apparel shoppers cannot physically assess garment fit prior to purchase. Inconsistent sizing across brands and styles, dense size charts, and static model photography leave shoppers uncertain about how a T-Shirt will actually fit their body—driving hesitation, cart abandonment, and size-related returns.

## Proposed Solution
- **Body Profile & Fit Preference:** Lightweight capture of height, chest measurement, optional weight, and preferred fit (`Slim`, `Regular`, or `Relaxed`).
- **Garment-Grounded Size Matching:** Deterministic size recommendations anchored in SKU-specific product dimensions and documented ease rules.
- **Transparent Recommendation Rationale:** Plain-language explanations detailing *why* a size is recommended (and clear guidance when a shopper falls between sizes).
- **Contextual Fit & Length Cues:** Estimated body/garment length indicators where reliable product dimension data exists.
- **Permissioned Personalization:** Optional integration of prior purchase and return signals with explicit user consent and deletion controls.
- **Future Scope — Visual Fit Simulation:** Optional CV/GenAI visual preview clearly labeled as an approximate simulation rather than a guaranteed fit.

---

## Research Snapshot
An exploratory 18-question Google Forms survey collected **16 submissions**, of which **$n = 14$ respondents** purchased T-Shirts online within the past 6 months and qualified for core analysis. Within this directional convenience sample:
- **85.7% (12/14)** have received an online T-Shirt that did not fit as expected (*frequently* or *sometimes*).
- **78.6% (11/14)** have returned or exchanged a T-Shirt *multiple times* due to size or fit issues.
- **78.6% (11/14)** cited **different sizing across brands** as their single biggest size-selection challenge.
- **85.7% (12/14)** selected **personalized size recommendations** as helpful, and **85.7% (12/14)** rated an explanation of *why* a size is recommended as `4` or `5` out of 5.
- **78.6% (11/14)** were comfortable providing **chest measurement**, and **71.4% (10/14)** were comfortable sharing **height** and **fit preference**.

> **Methodological Caveat:** This is a small, non-probability convenience sample and is not statistically representative of all online apparel shoppers. See `docs/02_research_plan_and_method.md` and `docs/03_survey_findings.md` for full methodology, denominators, and limitations.

---

## Repository Guide
| File | Purpose |
|---|---|
| `assets/` | UI concept mockup and survey data visualizations (`n = 14`) |
| `docs/01_problem_statement.md` | Problem framing, target segment, JTBD, goals & non-goals |
| `docs/02_research_plan_and_method.md` | Survey design, sampling method, limitations & follow-up research |
| `docs/03_survey_findings.md` | Quantitative & qualitative synthesis of Google Forms survey (`n = 14`) |
| `docs/04_external_research_and_references.md` | Industry literature context and cited evidence |
| `docs/05_product_requirements_document.md` | Product Requirements Document (PRD v2.0) |
| `docs/06_product_prioritization.md` | Impact vs. effort matrix and MVP vs. future scoping |
| `docs/07_product_backlog.md` | Epics, user stories, and acceptance criteria |
| `docs/08_user_journey_and_flows.md` | End-to-end user journey, Mermaid flow, and edge cases |
| `docs/09_technical_feasibility.md` | Proposed system architecture, feasibility, and data governance |
| `docs/10_figma_screen_plan.md` | Screen inventory, release phasing, and UX requirements |
| `docs/11_execution_roadmap.md` | 4-week prototype plan and MVP Definition of Done |
| `docs/12_metrics_and_experiment_plan.md` | North-star candidate, funnel KPIs, guardrails, and A/B test design |
| `docs/13_risks_assumptions_open_questions.md` | Risk register, core assumptions, and open product questions |
| `docs/14_portfolio_case_study.md` | Recruiter/HR-ready case-study summary |
| `data/survey_data_dictionary.md` | Survey schema, privacy rules, and denominator conventions |
| `references.md` | Academic and UX research bibliography |
| `LICENSE` | MIT license for original documentation |

---

## Product Principles
1. **Evidence over fabrication:** Ground recommendations strictly in verified product measurements; fall back gracefully when SKU dimensions are missing.
2. **Garment-first modeling:** Use chest and garment dimensions as primary sizing signals; treat BMI strictly as a supplementary metric.
3. **Honest AI boundaries:** Label any generated fit visual as an approximate simulation, never a photographic guarantee.
4. **Privacy by design:** Minimize personal data collection, gate purchase history behind explicit opt-in consent, and provide user edit/delete controls.
5. **Hypothesis-driven impact:** Treat conversion lift and return reduction as hypotheses to validate through testing—never pre-claimed outcomes.

## Presentation Disclaimer
Please reference this repository as an **independent Product Management case study / proposed product concept**. Do not claim official Myntra affiliation, production deployment, validated return-rate reductions, or live AI implementation.

## Author
## Randhir Kumar

**B.Tech — Metallurgical & Materials Engineering**  
**NIT Jamshedpur**
