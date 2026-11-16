# Product Backlog

Story points (SP) are relative planning estimates, not engineering commitments.

| ID | Epic / Story | Priority | SP |
|---|---|---:|---:|
| FC-01 | Body profile input form | P0 | 3 |
| FC-02 | Height/chest validation and unit conversion | P0 | 3 |
| FC-03 | Fit preference selector | P0 | 1 |
| FC-04 | Sample product size chart dataset | P0 | 5 |
| FC-05 | Rule-based recommendation logic | P0 | 8 |
| FC-06 | Recommendation explanation | P0 | 3 |
| FC-07 | Missing-data fallback | P0 | 3 |
| FC-08 | Edit profile/regenerate | P0 | 3 |
| FC-09 | Privacy/consent and data controls | P0 | 5 |
| FC-10 | Length cue using product dimensions | P1 | 5 |
| FC-11 | Fit feedback form | P1 | 3 |
| FC-12 | Purchase history personalization | P1 | 8 |
| FC-13 | Fit-review summary | P1 | 5 |
| FC-14 | CV fit estimation research/prototype | P2 | 13 |
| FC-15 | GenAI visual fit simulation | P2 | 13 |
| FC-16 | Visual result UI and safety labeling | P2 | 5 |

## Example acceptance criteria: FC-05
- Given valid body measurements, selected fit preference, and complete product size data, system returns a recommended size.
- Matching logic uses documented garment-ease assumptions.
- If measurements are between sizes, system applies a documented preference-aware rule or shows both sizes with rationale.
- If size data is absent or inconsistent, system does not return unsupported recommendation.
- Output includes size and explanation inputs used.

## Example acceptance criteria: FC-15
- Visual simulation is optional and non-blocking.
- Input references selected product and supported fit attributes.
- UI labels output “AI-generated fit simulation”.
- No claim of exact or guaranteed physical fit.
- If image generation fails, the size recommendation still displays.
