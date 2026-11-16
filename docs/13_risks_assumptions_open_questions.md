# Risks, Assumptions & Open Questions

## Risks
| Risk | Mitigation |
|---|---|
| Incomplete product dimensions | Fallback to size chart; no unsupported recommendation |
| User measurements inaccurate | Helper instructions, unit validation, edit profile |
| BMI is a weak sizing proxy | Use only supplementary; prioritize chest/garment dimensions |
| Purchase history unavailable | Use optional mocked data for prototype; do not imply Myntra integration |
| Generated visual inaccurate | Label simulation; non-blocking; test fidelity |
| CV data inadequate | Keep feature research/future scope until validated |
| Sensitive body/purchase data | Minimize, permission, secure, retention/deletion controls |
| Return reduction assumed | Define baseline and experiment; no guarantee |

## Assumptions
- Product-specific garment measurements can be collected for prototype products.
- Users can provide usable measurements.
- Fit preference changes the desired garment ease.
- Optional purchase-history context can improve recommendation only if accessible and relevant.
- Visual simulation could provide value, subject to evaluation.

## Open questions
1. Which measurement conventions will catalog data follow (garment vs body measurements)?
2. What ease thresholds map to Slim, Regular, Relaxed?
3. What should happen when a shopper falls between sizes?
4. How should recommendation confidence be calibrated?
5. How will fit prediction be validated against actual user feedback?
6. What data retention and consent standards are required?
7. Can product image generation preserve exact color, print, cut and brand details sufficiently?
