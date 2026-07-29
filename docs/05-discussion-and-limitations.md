# 5 · Discussion, Limitations & Policy Implication

[← Sensitivity analysis](04-sensitivity-analysis.md) · [Back to README](../README.md) · [Parameters →](parameters.md)

---

## Answering the research questions

**RQ1 — Primary cost-effectiveness.** The base-case analysis identifies angiography as the cost-effective strategy for the Sheffield severe-angina cohort at *every* threshold in the plausible UK range, including values below the NICE reference range that more credibly reflect NHS opportunity cost (Claxton et al., 2015). The INMB of ANG over MM is +£13,896 at λ = £30,000 and remains positive down to λ ≈ £6,232/QALY. The recommendation is therefore **not threshold-contingent** within the relevant policy range.

**RQ2 — Threshold and prevalence switching.** The two-way analysis locates the Sheffield cohort deep inside the ANG-optimal region of the prevalence × threshold surface. For the recommendation to flip to MM, both p(S) and λ would need to fall simultaneously to approximately 0.05 and £5,000 — a combination outside any plausible Sheffield scenario.

**RQ3 — Value of diagnostic accuracy.** The analysis yields a counter-intuitive but defensible result: EST sensitivity and specificity barely move the headline recommendation, because EST is already off the frontier in the comparison that matters. The marginal return to improving EST is ≈£1,380 per +0.10 sensitivity per patient, against ≈£3,615 per +0.10 in CABG success. **Surgery, not diagnosis, is where investment pays back.**

**RQ4 — Structural robustness and transferability.** The recommendation survives QALY discount rates up to 12–13% and a relaxation of the perfect-angiography assumption, but does *not* survive a simultaneous threshold-and-prevalence collapse — the scenario relevant to lower-income settings.

## Implications of assumptions and limitations

Four structural choices deserve explicit treatment for the decision-maker:

- **Static disease states (i)** bias the model *against* ANG by suppressing the long-term QALY gains from earlier accurate diagnosis; the recommendation is therefore *conservative* on this dimension, and a Markov extension would, if anything, strengthen it.
- **Perfect angiography (ii)** biases in the opposite direction, but the +£13,896 INMB cushion over MM is large enough that empirically plausible ANG accuracy (≈0.95–0.99) leaves the conclusion intact.
- **Rosser–Kind utilities (iii)** likely inflate absolute QALY totals modestly but affect strategy *differences* less, so the ranking is robust.
- **The absence of PSA (iv)** is the most consequential limitation: although the deterministic surface gives reasonable confidence that ANG would dominate the cost-effectiveness acceptability curve, the residual decision uncertainty has not been quantified and should be the priority for any follow-up.

## Policy implication

For the Sheffield department, the analysis supports **routine direct angiography for severe-angina referrals at the current cohort prior.** Where catheterisation capacity is constrained, EST retains value as a triage tool, but the analysis suggests the larger return on departmental investment lies in **improving CABG outcomes in MVD patients** rather than in upgrading the diagnostic pathway.

## Conclusion

Direct angiography is the cost-effective strategy for the Sheffield severe-angina cohort across the full plausible UK threshold range, with the recommendation robust to all single-parameter perturbations except a simultaneous collapse in prevalence and threshold. Priorities for further work are **probabilistic sensitivity analysis** with elicited input distributions, and a **Markov extension** to capture progression dynamics.

---

[← Sensitivity analysis](04-sensitivity-analysis.md) · [Back to README](../README.md) · [Parameters →](parameters.md)
