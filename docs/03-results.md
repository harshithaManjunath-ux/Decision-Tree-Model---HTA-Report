# 3 · Results

[← Methods](02-methods.md) · [Back to README](../README.md) · [Next: Sensitivity analysis →](04-sensitivity-analysis.md)

---

## Base-case strategy values

At base-case parameter values (p(S) = 0.90; EST sensitivity 0.85, specificity 0.90; 3.5% discounting), **all four strategies lie on the cost-effectiveness frontier** — none is dominated, and none is extended-dominated. The frontier is constructed by ordering strategies by ascending expected cost and computing ICERs sequentially.

| Strategy | Expected cost (£) | Expected QALYs | Incr. cost (£) | Incr. QALY | ICER (£/QALY) |
|---|---:|---:|---:|---:|---:|
| No Treatment (NT) | 0 | 2.602 | — | — | — |
| Medical Management (MM) | 1,189 | 5.075 | 1,189 | 2.473 | 481 |
| Exercise Stress Test (EST) | 4,255 | 5.573 | 3,065 | 0.498 | 6,159 |
| **Angiography (ANG)** | **4,855** | **5.661** | **600** | **0.088** | **6,845** |

The frontier reveals a useful structural feature: the ICER of **ANG vs EST (£6,845/QALY)** is fractionally *higher* than the ICER of **EST vs MM (£6,159/QALY)**, but the two are near-parity. This means that once a decision-maker is willing to fund EST, the additional move to ANG is essentially the same value-for-money trade-off — not a more demanding one. Both lie far below the lower end of the NICE threshold range (£20,000–£30,000/QALY) and well below the more realistic estimate of health opportunity cost in the NHS (≈£12,936/QALY; Claxton et al., 2015).

![Cost-effectiveness plane and frontier](../figures/fig3-ce-plane.png)

*All four strategies lie on the cost-effectiveness frontier; segment slopes are the ICERs. The dashed line is the willingness-to-pay reference at λ = £30,000/QALY through the comparator. All frontier segments are flatter than the WTP line, indicating cost-effectiveness at every threshold ≥ ≈£6,300/QALY.*

## Net monetary benefit and the recommendation

Translating the frontier into net monetary benefit collapses the multi-strategy comparison into a single ranking at each threshold, avoiding the error-prone exclusion logic required for fully incremental ICERs.

| Threshold (λ) | NT | MM | EST | ANG | Optimal |
|---:|---:|---:|---:|---:|:--|
| £5,000 | 11,823 | 21,122 | 23,011 | **28,304** | ANG |
| £10,000 | 26,025 | 49,564 | 51,476 | **51,753** | ANG |
| £15,000 | 39,037 | 74,941 | 79,341 | **80,056** | ANG |
| £20,000 | 52,049 | 100,318 | 107,207 | **108,360** | ANG |
| £25,000 | 65,061 | 125,694 | 135,072 | **136,663** | ANG |
| £30,000 | 78,074 | 151,071 | 162,938 | **164,967** | ANG |
| £35,000 | 91,086 | 176,448 | 190,803 | **193,280** | ANG |

**Angiography maximises NMB at every threshold tested.** The incremental net monetary benefit of ANG over MM rises from **+£7,235 at λ = £5,000 to +£16,822 at £35,000**. The economic gap between ANG and the second-best strategy, however, narrows sharply with the threshold: at λ = £30,000 the INMB of ANG over EST is only +£2,029, whereas the gap over MM is +£13,896. The practical reading is that once the decision-maker accepts ANG over MM, the marginal case for choosing ANG *specifically over EST* is real but modest, and depends on the value placed on the additional 0.088 QALYs that perfect diagnostic information delivers.

![Net monetary benefit across thresholds](../figures/fig4-nmb-thresholds.png)

*Lines for MM, EST, and ANG fan out roughly in parallel because they share most of the QALY mass; the vertical distance between ANG and MM widens with λ, reflecting the increasing monetary valuation of ANG's QALY gain. ANG remains the upper envelope across the full plausible UK range.*

## Base-case conclusion (RQ1)

The base-case recommendation is unambiguous: **angiography is the cost-effective strategy at every threshold in the plausible UK range**, with INMB over the next-best strategy ranging from +£330 (at £10,000) to +£2,520 (at £35,000), and INMB over the status quo of medical management ranging from +£7,235 to +£16,822. Whether the strength of that recommendation survives uncertainty in the key inputs is the question the [sensitivity analysis](04-sensitivity-analysis.md) addresses.

---

[← Methods](02-methods.md) · [Back to README](../README.md) · [Next: Sensitivity analysis →](04-sensitivity-analysis.md)
