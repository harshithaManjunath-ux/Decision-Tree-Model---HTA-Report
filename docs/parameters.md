# Model Parameters — Full Table with Sensitivity Ranges & Sources

[← Back to README](../README.md) · [Discussion](05-discussion-and-limitations.md)

This consolidates all model inputs used in the base-case analysis and the one-way deterministic sensitivity analysis. Bounds for the latter are drawn from clinically plausible ranges in the Sheffield case study unless otherwise indicated. All monetary values in GBP.

## Probability inputs

| Parameter | Base case | Low | High | Source / basis |
|---|---:|---:|---:|---|
| Prior probability of disease, p(S) | 0.90 | 0.00 | 1.00 | Sheffield case study; full range explored for heterogeneity |
| P(SVD \| sick) | 0.10 | 0.05 | 0.20 | Sheffield case study |
| P(MVD \| sick) | 0.90 | 0.80 | 0.95 | Sheffield case study |
| EST sensitivity, P(+ \| sick) | 0.85 | 0.70 | 1.00 | Sheffield case study; range reflects published EST performance |
| EST specificity, P(− \| healthy) | 0.90 | 0.80 | 1.00 | Sheffield case study |
| ANG sensitivity / specificity | 1.00 / 1.00 | 0.95 / 0.95 | 1.00 / 1.00 | Structural assumption; relaxed in sensitivity analysis |
| CABG success rate — SVD | 0.85 | 0.75 | 0.95 | Sheffield case study |
| CABG success rate — MVD | 0.70 | 0.50 | 0.90 | Sheffield case study |
| Procedure mortality — CABG (SVD) | 0.03 | 0.01 | 0.05 | Sheffield case study |
| Procedure mortality — CABG (MVD) | 0.08 | 0.04 | 0.16 | Sheffield case study |
| Procedure mortality — ANG | 0.0003 | 0.0001 | 0.001 | Sheffield case study |
| Procedure mortality — no disease | 0.0002 | 0.0001 | 0.0005 | Sheffield case study |

## Cost inputs (GBP)

| Parameter | Base case | Low | High | Source / basis |
|---|---:|---:|---:|---|
| Exercise stress test (EST), unit cost | 53 | 40 | 80 | Sheffield case study |
| Angiography (ANG), unit cost | 668 | 500 | 900 | Sheffield case study |
| CABG procedure, unit cost | 3,527 | 2,800 | 4,500 | Sheffield case study |
| MM — post-CABG success, annual | 107 | 80 | 150 | Sheffield case study |
| MM — severe / CABG failure, annual | 214 | 160 | 300 | Sheffield case study |
| MM — healthy / no treatment, annual | 214 | 160 | 300 | Sheffield case study |
| No treatment | 0 | — | — | By definition |

**Discounted maintenance totals** (annual costs discounted at 3.5% p.a.): post-CABG success £890 (10 yr); severe / CABG failure £1,780 (10 yr); healthy / no treatment £2,465 (15 yr).

## Utility inputs (QALY weights)

Rosser–Kind utility weights (Kind, Rosser & Williams, 1982). The current NICE reference standard is EQ-5D. Discounted QALY totals by pathway:

| Health pathway | Total QALYs (disc.) | Rosser states |
|---|---:|---|
| SVD → CABG (success) → MM | 8.16 | IA → IIC → IIIC |
| MVD → CABG (success) → MM | 5.60 | IB → IIA → IVC |
| SVD → MM (no surgery) | 7.61 | IIB → IVC → VD |
| MVD → MM (no surgery) | 4.01 | IIIC → IVD → VD |
| SVD → No treatment | 4.28 | VD → VID |
| MVD → No treatment | 1.33 | VD → VID → 0 |
| Healthy — any strategy | 11.40 | IA → IIB (15-yr horizon) |

## Discount rates

| Parameter | Base case | Low | High | Source |
|---|---:|---:|---:|---|
| Cost discount rate | 3.5% | 0% | 21% | NICE reference case (2022) |
| QALY discount rate | 3.5% | 0% | 21% | NICE reference case (2022) |

## Decision rule & horizon

| Parameter | Base case | Low | High | Source |
|---|---:|---:|---:|---|
| Cost-effectiveness threshold, λ | £20,000–£30,000 | £5,000 | £35,000 | NICE reference range; lower bounds reflect Claxton et al. (2015) opportunity-cost estimate |
| Time horizon — post-CABG success | 10 years | — | — | Sheffield case study |
| Time horizon — healthy / no treatment | 15 years | — | — | Sheffield case study |

---

*Base-case EST posteriors (from Bayesian revision): P(S \| EST+) = 0.987, P(S \| EST−) = 0.600, with marginal P(EST+) = 0.775 and P(EST−) = 0.225.*

[← Back to README](../README.md) · [Discussion](05-discussion-and-limitations.md)
