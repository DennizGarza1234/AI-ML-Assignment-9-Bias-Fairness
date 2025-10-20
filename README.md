# AI-ML Assignment 9: Bias and Fairness
**Author:** Denniz Garza  
**Dataset:** Adult Census Income  
**Fairness Library:** AIF360  

---

## Overview
This project investigates **bias detection and mitigation** in a machine-learning model.  
We examine how fairness interventions affect model accuracy using the Adult Census Income dataset.

---

## Sensitive Attribute
- **Attribute:** sex  
- **Privileged Group:** Male  
- **Unprivileged Group:** Female  

---

## Summary of Results

| Model | Accuracy | Disparate Impact | Statistical Parity Difference |
|:------|:---------:|:----------------:|:-----------------------------:|
| **Baseline** | 0.82 | 0.65 | −0.21 |
| **Mitigated (Reweighing)** | 0.80 | 0.95 | −0.05 |

---

## Fairness – Accuracy Trade-off
Bias mitigation improved fairness (Disparate Impact ↑ from 0.65 to 0.95,  
SPD ↑ from −0.21 to −0.05) with a slight 2 % drop in accuracy.  
This demonstrates the **typical fairness-accuracy trade-off**: improving equality of outcomes may slightly reduce predictive performance.

---

## Requirements

---

## Youtube Link
