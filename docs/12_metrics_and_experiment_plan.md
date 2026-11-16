# Metrics & Experiment Plan

## North-star candidate
**Fit Satisfaction Rate:** share of feedback respondents reporting “fit as expected” among users who purchased after using FitConfidence. This is a candidate metric and requires feedback collection.

## Funnel metrics
- Eligible PDP visitor → FitConfidence start (adoption)
- Start → completed profile (completion)
- Completed profile → recommendation shown (successful result rate)
- Recommendation shown → add to cart (post-recommendation ATC)
- Purchase → fit feedback submitted (feedback rate)

## Product quality metrics
- Recommendation agreement with user feedback.
- Rate of fallback due to missing product data.
- Fit dissatisfaction by product/size.
- Visual simulation helpfulness and mismatch reports (advanced).

## Guardrails
- Overall conversion and checkout abandonment.
- Total return rate and size-related return rate (if accessible).
- Complaints or distrust caused by recommendations.
- Privacy opt-out and deletion requests.
- AI visual dissatisfaction.

## Experiment concept
A/B test (only with platform access and adequate sample):
- Control: existing size chart/size selection experience.
- Treatment: FitConfidence recommendation.
- Primary outcome: fit satisfaction or recommendation adoption; return rate can be a secondary metric with enough follow-up.
- Guardrails: conversion, returns, complaints, and user privacy.
- Segment cautiously; avoid interpreting underpowered results.

## Hypothesis
If shoppers receive transparent, product-data-grounded recommendations, they may feel more confident and report improved fit satisfaction. Reduction in returns is an outcome to measure, not an assumption.
