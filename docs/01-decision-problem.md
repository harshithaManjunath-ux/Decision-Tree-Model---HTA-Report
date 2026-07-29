# 1 · The Decision Problem

[← Back to README](../README.md) · [Next: Methods →](02-methods.md)

---

## Context and rationale

The perspective of this evaluation is a **cardiology department in Sheffield**. All patients are male, aged 55, referred with typical severe exertional angina, and carry a high prior probability of obstructive coronary artery disease, **p(S) = 0.90**. The department must decide how to investigate and treat these patients given finite resources — where every pound spent on diagnosis or surgery displaces health that could be generated elsewhere in the local system.

The decision is non-trivial because the available strategies differ sharply in *both* cost *and* the quality of the information they yield. The central tension is between **diagnostic precision and resource efficiency**:

- **Coronary angiography (ANG)** is assumed to provide perfect information on coronary anatomy, but is invasive, carries a small procedural mortality risk, and is capital-intensive.
- **Exercise stress test (EST)** is non-invasive and far cheaper, but imperfect (sensitivity 0.85, specificity 0.90) — generating false negatives that delay treatment and false positives that trigger unnecessary surgery.
- **Medical management (MM)** treats without formal diagnosis.
- **No treatment (NT)** is the baseline comparator.

This decision problem mirrors questions addressed in the published UK literature. Walker et al. (2013), evaluating sequential diagnostic strategies for suspected angina in an NHS cardiology setting (the CE-MARC study), found that the cost-effective strategy was highly sensitive to *both* the willingness-to-pay threshold *and* the prior likelihood of disease — the same two levers that drive the present analysis. That finding motivates a structured interrogation of how the Sheffield recommendation responds to these parameters, rather than a single base-case verdict.

## The four strategies

| Strategy | Description | Downstream treatment |
|---|---|---|
| **No Treatment (NT)** | Baseline — no diagnostic test or active treatment | — |
| **Medical Management (MM)** | Direct medical management without prior diagnostic testing | — |
| **Exercise Stress Test (EST)** | Non-invasive imperfect test | → Angiography or MM depending on result |
| **Coronary Angiography (ANG)** | Invasive perfect test | → CABG or MM depending on disease confirmed |

Disease, when present, is either **single-vessel disease (SVD)** or **multi-vessel disease (MVD)**; post-diagnosis, patients may receive **coronary artery bypass graft surgery (CABG)** or medical management.

## Research questions

Four research questions are addressed, ordered by analytic priority. RQ1–RQ2 constitute the primary analysis for the Sheffield cohort; RQ3–RQ4 form the sensitivity, robustness, and transferability analyses.

- **RQ1 — Primary cost-effectiveness (Sheffield base case).** Which of ANG, EST, MM, and NT is cost-effective for the severe-angina cohort at thresholds spanning the plausible UK range, including values below the NICE reference range that better reflect true health opportunity cost?
- **RQ2 — Threshold and prevalence switching.** At what combination of disease prevalence and λ does the optimal strategy switch between ANG, EST, and MM?
- **RQ3 — Value of diagnostic accuracy.** How do EST sensitivity and specificity affect the recommendation, and is there an economically meaningful return to improving EST performance?
- **RQ4 — Structural robustness and transferability.** How sensitive is the conclusion to the discount rate and the perfect-angiography assumption; and how might the recommendation change in a lower-income setting where the threshold is lower and catheterisation capacity is scarcer?

---

[← Back to README](../README.md) · [Next: Methods →](02-methods.md)
