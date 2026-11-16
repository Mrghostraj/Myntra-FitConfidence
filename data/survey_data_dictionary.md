# Survey Data Dictionary

## Source & Governance
* **Source Workbook:** `Myntra FitConfidence — User Research Survey (Responses)` (Google Forms export)[cite: 3].
* **Privacy Rule:** Do not commit raw response spreadsheets, timestamps, respondent identifiers, or row-level export tables to public repositories[cite: 3]. Only aggregated metrics and anonymized qualitative themes are published in `docs/03_survey_findings.md`.

## Sample & Denominator Rules
* **Total Form Submissions (`N`):** 16
* **Screening Question (`Q2`):** *"Have you purchased T-Shirts online in the last 6 months?"*[cite: 3]
  * `Yes`: **14 respondents** — routed to `Q3–Q18` (core analysis sample, $n = 14$).
  * `No`: **2 respondents** — exited survey after `Q4` (`Q5–Q18` intentionally blank).
* **Percentage Calculation:** All percentages in `docs/03_survey_findings.md` use **$n = 14$** (qualified active online T-Shirt buyers) as the denominator[cite: 3]. For multi-select fields (`Q3`, `Q8`, `Q10`, `Q13`, `Q14`, `Q16`), percentages reflect the share of the 14 respondents who selected each option[cite: 3].

## Schema Reference

| Col | Question ID | Full Survey Question | Response Type | Values / Scale |
|---|---|---|---|---|
| `A` | Metadata | Timestamp | DateTime | Excluded from public docs[cite: 3] |
| `B` | `Q1` | What is your age group? | Single-select | `Below 18`, `18–21`, `22–25`, `26–30`, `31+` |
| `C` | `Q2` | Have you purchased T-Shirts online in the last 6 months? | Screening (`Yes`/`No`) | Gates `Q5–Q18` (`Yes` = $n=14$) |
| `D` | `Q3` | Which platforms do you use to purchase T-Shirts online? | Multi-select | Myntra, Amazon, Flipkart, Ajio, Brand websites (e.g., H&M, Zara), Other |
| `E` | `Q4` | How frequently do you purchase T-Shirts online? | Single-select | More than once a month; Once a month; Once every 2–3 months; Occasionally (< once every 3 months) |
| `F` | `Q5` | How do you usually decide which T-Shirt size to purchase? | Single-select | Check size chart; Select usual size; Use size recommendation feature; Guess from product images |
| `G` | `Q6` | How confident are you that you select the correct T-Shirt size when shopping online? | Likert (`1–5`) | `1` = Not confident at all → `5` = Very confident |
| `H` | `Q7` | Have you ever received a T-Shirt that did not fit as expected? | Single-select | `Never`, `Rarely`, `Sometimes`, `Frequently` |
| `I` | `Q8` | What fit-related problems have you experienced with online T-Shirt purchases? | Multi-select | Cross-brand size differences, confusing chart, too loose/tight, length too long/short, sleeve fit, shrinkage, none |
| `J` | `Q9` | Have you ever returned or exchanged a T-Shirt because of its size or fit? | Single-select | `No`, `Yes, once`, `Yes, multiple times` |
| `K` | `Q10` | What do you do when you are unsure about the size of a T-Shirt? | Multi-select | Check chart, read reviews, ask friends/family, order usual size anyway, avoid purchase, order multiple sizes, search online |
| `L` | `Q11` | How useful do you find the existing size charts on shopping apps? | Likert (`1–5`) | `1` = Not useful at all → `5` = Very useful |
| `M` | `Q12` | What is the biggest challenge you face while selecting a T-Shirt size online? | Single-select | Different sizing across brands; Uncertainty about how it will look on me; Lack of fit-related reviews |
| `N` | `Q13` | Which information would be most helpful when selecting a T-Shirt size? | Multi-select | Personalized recommendation; Visual fit representation; Runs Small/True/Large tag; Cross-brand size comparison; Fit review summary |
| `O` | `Q14` | Which information would you be comfortable providing for a personalized size recommendation? | Multi-select | Fit preference (Slim/Regular/Relaxed); Chest; Height; Weight; Previous purchase info; Usual T-Shirt size |
| `P` | `Q15` | How useful would a feature that explains why a particular size is recommended be to you? | Likert (`1–5`) | `1` = Not useful at all → `5` = Very useful |
| `Q` | `Q16` | What would make you trust a size recommendation on a shopping app? | Multi-select | Based on previous purchases; Based on actual measurements; Clear explanation; Cross-brand accuracy; Customer fit feedback; Post-purchase feedback loop |
| `R` | `Q17` | If you could improve one thing about the online T-Shirt shopping experience, what would it be? | Open text | Coded into qualitative themes in `docs/03_survey_findings.md` |
| `S` | `Q18` | Any additional suggestions regarding size selection or fit guidance? | Open text | Coded into qualitative themes in `docs/03_survey_findings.md` |
