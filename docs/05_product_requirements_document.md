# Product Requirements Document (PRD)
## Myntra FitConfidence — Personalized Size Recommendation & Visual Fit Intelligence

**Version:** 2.0 | **Status:** Draft concept | **Category:** Men's T-Shirts

## 1. Product overview
Proposed feature that helps shoppers choose a Men's T-Shirt size by matching a user body profile and fit preference against product-specific garment measurements. It can explain the recommendation and, in an advanced phase, provide fit estimation and AI visual simulation.

## 2. Problem
Online shoppers may be uncertain about size because sizing varies across brands/styles, size charts can be hard to interpret, and product information may not translate measurements into a person's preferred fit.

## 3. Target user
Online Men's T-Shirt shoppers who experience size-selection uncertainty or prior fit mismatch. This is a hypothesized segment, informed directionally by an exploratory n=14 survey.

## 4. Goals
- Provide a transparent, data-grounded size suggestion.
- Use garment-specific size information.
- Incorporate fit preference and relevant measurements.
- Make personalization optional and user-controlled.
- Explore visual fit cues only with honest uncertainty labeling.
- Measure recommendation adoption and fit satisfaction.

## 5. Non-goals
All apparel categories, guaranteed fit, medical BMI interpretation, production Myntra integration, full virtual try-on, AI body scanning, and automated size data extraction for every catalog item.

## 6. Proposed user inputs
- Height (required in the proposed flow)
- Chest measurement (required)
- Fit preference: Slim / Regular / Relaxed
- Weight (optional; BMI only supplementary)
- Usual size (optional)
- Previous purchases/fit feedback (optional, permission-dependent)

BMI is calculated only when height and weight are provided; it is not a primary sizing signal and does not reliably describe chest/shoulder proportions.

## 7. Core feature requirements
### P0: Core recommendation
- User enters measurements and preference.
- System validates units/ranges.
- System compares user inputs with reliable product-specific size data.
- System recommends a size or provides a fallback when data is insufficient.
- System shows a rationale grounded in the data.
- User can edit inputs and regenerate.
- No fabricated size data or confidence score.

### P1: Enhanced product context
- Product garment measurements (chest, shoulder, sleeve, length) considered where available.
- Approximate length cue may be shown only with a defined rule and sufficient data.
- Optional fit feedback collection.
- Optional previous-purchase signals only with authorization and controls.

### P2: Advanced AI
- CV-based fit estimation researched and evaluated on suitable data.
- GenAI visual fit simulation can use selected product and fit attributes.
- Visual output is labeled as a simulation; it is not a guarantee of physical fit.
- Failure of AI image generation must not block core recommendation.

## 8. User stories
1. As a shopper, I want to enter body measurements and fit preference to get a size suggestion.
2. As a returning shopper, I want my authorized purchase history to inform recommendations without assuming previous size was correct.
3. As a shopper, I want garment dimensions and length cues to understand expected fit.
4. As a shopper, I want an estimated fit classification where evidence supports it.
5. As a shopper, I want an optional AI visual simulation to contextualize expected fit.
6. As a shopper, I want to understand the reasons behind the suggested size.

## 9. Acceptance criteria
- Measurements can be entered in cm/inches with conversion and validation.
- Slim / Regular / Relaxed is selectable.
- BMI is supplementary only.
- Recommendation is generated only when reliable product sizing data exists.
- Explanation references actual input and garment data.
- Missing data results in fallback, not invented recommendation.
- Purchase history use is optional, permission-based, and editable.
- Fit/length estimates are labeled approximate.
- AI visuals are labeled generated simulations and may not claim exact fit.
- User can dismiss visual generation; core result remains accessible.

## 10. User journey
Product detail page → Find My Fit → profile measurements → fit preference → data validation → retrieve product sizing → recommendation engine → recommended size + rationale → optional fit simulation → size selection/cart → optional post-purchase feedback.

## 11. Success metrics (proposed)
- Recommendation adoption = users who use FitConfidence / eligible product detail visitors.
- Completion rate = users receiving recommendation / users starting flow.
- Fit satisfaction = “fit as expected” feedback / feedback submissions.
- Add-to-cart rate after recommendation.
- Fit simulation engagement rate (advanced).
- Size-related returns/exchanges, if data is available, evaluated against baseline/control.

## 12. Guardrails
- Overall conversion, checkout abandonment, total return rate, recommendation complaints, privacy opt-outs, and visual simulation dissatisfaction.
- Return reduction is not guaranteed; validate with a controlled or well-designed comparison.

## 13. Dependencies
Product-specific garment measurements, catalog size chart data, recommendation logic, UX/UI, backend, authorized purchase-history access, feedback collection, AI/CV evaluation dataset for advanced features, and privacy/security review.

## 14. Risks
Inaccurate measurements, sparse catalog data, variation in garment production, weak fit logic, misleading image simulation, user input friction, privacy concerns, and model/data limitations.

## 15. Open questions
- What garment dimensions are reliably available per SKU/size?
- How should between-size cases be handled?
- What accuracy threshold and validation dataset are needed?
- How should historical purchases be weighted?
- How will visual outputs be evaluated for product fidelity and fit?
- What data retention and deletion controls are required?
