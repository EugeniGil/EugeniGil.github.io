---
title: "Transparent policy evaluation through causal machine learning: An application to SME digital subsidies"
collection: talks
type: "Conference talk"
permalink: /talks/2026-09-08-data-for-policy
venue: "Data for Policy 2026 (DfP'26), Universitat Pompeu Fabra"
date: 2026-09-08
location: "Barcelona, Spain"
---

Talk given at the 10th **Data for Policy** conference (8–10 September 2026), whose theme is
*Governance of/with AI: Implications for Data, Infrastructure, and Tech Sovereignty*.
Joint work with Ana Garcia-Bernabeu and Pablo de Pedraza.

## Abstract

Causal machine learning gives an effect for every firm, but it gives no account of *why*.
We evaluate Spain's **Kit Digital** voucher — €3.07 bn of Next Generation EU funds, 200,000+
beneficiary SMEs — with a causal random forest, and add a transparency layer that makes the
estimator auditable:

1. **Explain it** — SHAP attributes each firm's estimate to its own characteristics.
2. **Summarise it** — a best linear projection turns 65,131 individual effects into
   coefficients with valid standard errors.
3. **Stress-test it** — overlap, pre-treatment trends and sensitivity to unobserved confounding.

The evidence comes from two administrative registries (BDNS subsidy records + SABI firm
accounts) linked into a firm-level panel for 2019–2024: 13,530 firms treated in 2022 against
51,601 never-treated.

## Main findings

- Employment rises **+4.3%** two years after treatment (*p* = 0.01); 92.9% of firms have a
  positive estimated effect.
- The gain is concentrated in **micro and small firms** — a pattern the model discovers rather
  than one imposed by the specification.
- Revenues and value added share the sign but do not survive a modest amount of unobserved
  confounding; overturning the employment result would take a confounder ~6× stronger than
  anything observed.

## Materials

- [Slides (PDF)](/files/dfp2026_transparent_policy_evaluation.pdf)
- [Working paper](https://doi.org/10.21203/rs.3.rs-9912144/v1)
- [Replication code](https://github.com/EugeniGil/research-code)
