# Primary User Research: Survey Findings

## 1. Study Overview & Sample Profile
An exploratory Google Forms survey (`Myntra FitConfidence — User Research Survey`) was conducted to understand online T-Shirt sizing friction, current decision-making workarounds, and trust drivers for personalized fit recommendations[cite: 3].

* **Total Submissions:** $N = 16$
* **Screening Logic:** Q2 filtered respondents based on whether they had purchased T-Shirts online within the past 6 months[cite: 3].
* **Qualified Analysis Sample:** **$n = 14$ (87.5%)** answered "Yes" and completed the full 18-question survey[cite: 3]. Two respondents (12.5%) answered "No" and exited at screening.
* **Methodological Note:** This is a small, non-probability convenience sample[cite: 1]. All percentages below use **$n = 14$** as the denominator and represent directional user research signals rather than market-wide estimates[cite: 3, 10]. Multi-select questions allow overlapping responses and therefore sum to more than 100%[cite: 3].

### Respondent Demographics & Shopping Context ($n = 14$)
* **Age Distribution:**
  * **22–25:** 6 respondents (42.9%)
  * **18–21:** 5 respondents (35.7%)
  * **Below 18:** 2 respondents (14.3%)
  * **26–30:** 1 respondent (7.1%)
* **Platforms Used (Multi-Select, Q3):**
  * **Flipkart:** 10/14 (71.4%)
  * **Amazon:** 8/14 (57.1%)
  * **Myntra:** 7/14 (50.0%)
  * **Brand Websites (e.g., H&M, Zara):** 4/14 (28.6%)
  * **Ajio:** 3/14 (21.4%)
* **Purchase Frequency (Q4):**
  * **Once every 2–3 months:** 7/14 (50.0%)
  * **Occasionally (less than once every 3 months):** 4/14 (28.6%)
  * **More than once a month:** 2/14 (14.3%)
  * **Once a month:** 1/14 (7.1%)

---

## 2. Current Size Selection Behavior & Confidence

### How Shoppers Choose a Size (Q5)
* **I check the size chart:** 6/14 (42.9%)
* **I select my usual size:** 4/14 (28.6%)
* **I use a size recommendation feature:** 3/14 (21.4%)
* **I guess based on product images:** 1/14 (7.1%)

### Confidence vs. Existing Size Chart Utility (5-Point Scales)
| Metric | Mean Score | Distribution ($n = 14$) | Key Takeaway |
|---|---|---|---|
| **Q6. Confidence in selecting correct size** | **3.07 / 5.0** | `1`: 7.1% (1) \| `2`: 14.3% (2) \| `3`: 28.6% (4) \| `4`: 50.0% (7) \| `5`: 0.0% (0) | **0% of respondents** felt "very confident" (`5/5`); half sit at moderate-to-low confidence (`1–3`). |
| **Q11. Usefulness of existing size charts** | **3.36 / 5.0** | `1`: 0.0% (0) \| `2`: 7.1% (1) \| `3`: 42.9% (6) \| `4`: 50.0% (7) \| `5`: 0.0% (0) | Size charts are viewed as moderately helpful (`3–4`), but never rated `5/5` due to cross-brand inconsistency. |

---

## 3. Core Pain Points & Downstream Impact

### Fit Mismatch & Return Frequency
* **Unexpected Fit Frequency (Q7):** **12/14 (85.7%)** have received a T-Shirt that did not fit as expected—**5/14 (35.7%) *Frequently***, **7/14 (50.0%) *Sometimes***, and **2/14 (14.3%) *Rarely***.
* **Size/Fit Returns & Exchanges (Q9):** **100% of active buyers (14/14)** have returned or exchanged a T-Shirt due to size or fit:
  * **Yes, multiple times:** 10/14 (71.4%)
  * **Yes, once:** 4/14 (28.6%)

### Specific Fit Problems Experienced (Multi-Select, Q8)
| Fit Problem | Count ($n=14$) | Share |
|---|---|---|
| **Size differed across brands** | 11 | **78.6%** |
| **Size chart was confusing** | 5 | **35.7%** |
| **T-Shirt was too loose** | 5 | **35.7%** |
| **Length was too long** | 3 | **21.4%** |
| **Length was too short** | 1 | **7.1%** |
| **T-Shirt was too tight** | 1 | **7.1%** |
| **Sleeve fit was uncomfortable** | 1 | **7.1%** |
| **Shrinkage after wash** | 1 | **7.1%** |
| *No fit-related problems* | 2* | *14.3%* |

*\*Note: One respondent selected "No fit-related problems" alongside specific sizing issues.*

### Single Biggest Challenge in Size Selection (Q12)
1. **Different sizing across brands:** **10/14 (71.4%)**
2. **Uncertainty about how the T-Shirt will look on me:** **3/14 (21.4%)**
3. **Lack of fit-related customer reviews:** **1/14 (7.1%)**

### Coping Behaviors & Cart Abandonment When Unsure (Multi-Select, Q10)
When uncertain about sizing, shoppers fall back on high-friction workarounds or abandon the purchase:
* **Check the size chart:** 8/14 (57.1%)
* **Read customer reviews:** 8/14 (57.1%)
* **Ask friends/family:** 7/14 (50.0%)
* **Order my usual size anyway:** 4/14 (28.6%)
* **Avoid purchasing the product (abandonment):** 4/14 (28.6%)
* **Search for product details online:** 1/14 (7.1%)
* **Order multiple sizes (bracketing):** 1/14 (7.1%)

---

## 4. Feature Demand, Data Sharing Comfort & Trust Drivers

### Most Helpful Information for Size Selection (Multi-Select, Q13)
| Desired Information / Feature | Count ($n=14$) | Share | Maps to FitConfidence Scope |
|---|---|---|---|
| **Personalized size recommendation** | 11 | **78.6%** | Core MVP Recommendation Engine |
| **Visual representation of the expected fit** | 8 | **57.1%** | Future Scope (GenAI Fit Simulation) |
| **Clear indication: Runs Small / True to Size / Runs Large** | 6 | **42.9%** | MVP Garment Ease & Fit Cues |
| **Comparison with my usual size across brands** | 6 | **42.9%** | P1 / Authorized Purchase History |
| **Fit-related customer review summary** | 4 | **28.6%** | P1 / Future NLP Review Summary |

### Inputs Users Are Comfortable Providing (Multi-Select, Q14)
| Personal Input | Count ($n=14$) | Share | Product Design Implication |
|---|---|---|---|
| **Fit preference (Slim / Regular / Relaxed)** | 10 | **71.4%** | Mandatory core input (low friction, high signal) |
| **Chest measurement** | 9 | **64.3%** | Primary garment-matching anchor |
| **Height** | 8 | **57.1%** | Core input for garment length estimation |
| **Weight** | 6 | **42.9%** | Keep **optional** (highest drop-off risk among body metrics) |
| **Previous purchase information (if available)** | 5 | **35.7%** | Strictly **opt-in / permissioned** |
| **My usual T-Shirt size** | 4 | **28.6%** | Useful fallback/baseline anchor |

### Demand for Explainability & Trust Signals (Q15 & Q16)
* **Usefulness of Recommendation Explanation (Q15):** Rated **4.29 / 5.0** on average—the highest-scoring Likert item in the survey:
  * `5` (Extremely useful): **6/14 (42.9%)**
  * `4` (Very useful): **6/14 (42.9%)**
  * `3` (Moderately useful): **2/14 (14.3%)**
  * **85.7% (12/14)** rated recommendation explanations `4` or `5` out of 5.
* **What Builds Trust in a Size Recommendation (Multi-Select, Q16):**
  1. **Recommendations based on my previous purchases:** 11/14 (78.6%)
  2. **Recommendations based on actual measurements:** 9/14 (64.3%)
  3. **Clear explanation of why the size is recommended:** 7/14 (50.0%)
  4. **High accuracy across different brands:** 6/14 (42.9%)
  5. **Fit feedback from other customers:** 4/14 (28.6%)
  6. **Ability to provide feedback after purchase:** 2/14 (14.3%)

---

## 5. Qualitative Synthesis (Q17 & Q18)
Open-ended responses clustered around four actionable product themes:
1. **Visual Fit & Drape Certainty (5 mentions):** Respondents repeatedly asked for *"visual representations of the expected fit"* and *"AI to check if this T-Shirt is fit for me or not"* to eliminate guesswork on how a garment drapes on their body.
2. **Multi-Part Measurement Friction (1 detailed insight):** One respondent highlighted that standard size charts require measuring shoulder, chest, waist, and arm length—which rarely map to a single standard size—suggesting custom-fit guidance or smarter multi-point reconciliation.
3. **Measurement & Sizing Standardization (2 mentions):** Users requested *"accurate, standardized, and interactive sizing"* across brands.
4. **Fabric & Quality Assurance (4 mentions — Out-of-Scope Guardrail):** Several users cited fabric quality, color bleeding, and post-wash shrinkage (`Q8`, `Q17`, `Q18`). While shrinkage impacts post-wash fit, fabric durability is documented as a separate catalog quality concern rather than a sizing-engine feature.

---

## 6. How Survey Findings Shape Product Decisions
* **Prioritize Explainable Measurement Matching in MVP:** Because **85.7%** value explanations (`4–5/5`) and **64.3%** trust recommendations grounded in actual measurements, the MVP centers on deterministic garment-to-body measurement rules paired with plain-language rationale.
* **Make Weight Optional & Purchase History Opt-In:** Users are far more willing to share fit preference (**71.4%**) and chest/height (**64.3% / 57.1%**) than weight (**42.9%**) or purchase history (**35.7%**). Making weight optional and purchase history permission-gated respects user comfort while preserving recommendation trust (**78.6%** cite purchase history as a top trust driver).
* **Stage Visual Fit Simulation as Post-MVP:** While **57.1%** want visual fit representations, generative visual accuracy is technically high-risk and must be clearly labeled as an estimate after the core sizing engine is validated[cite: 6, 9].
