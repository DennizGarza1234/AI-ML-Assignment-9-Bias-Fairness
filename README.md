# AI-ML Assignment 9: Bias and Fairness
**Author:** Denniz Garza  
**Dataset:** Adult Census Income
**Fairness Tool:** AIF360

## Summary
We trained a baseline classifier to predict income >50K. We analyzed fairness metrics and applied a mitigation technique to reduce bias.

---

## Sensitive Attribute
- **Attribute:** sex  
- **Privileged Group:** Male  
- **Unprivileged Group:** Female

  ---

## Comparison of Models

| Model        | Accuracy | Disparate Impact | Statistical Parity Difference |
|--------------|---------|----------------|-------------------------------|
| Baseline     | 0.82    | 0.65           | -0.21                        |
| Mitigated    | 0.80    | 0.95           | -0.05                        |

---

## Fairness-Accuracy Trade-off
Applying reweighting reduced bias significantly (Disparate Impact improved from 0.65 → 0.95), but Accuracy dropped slightly (0.82 → 0.80), illustrating the common trade-off between fairness and predictive performance.

---

## Youtube Link
