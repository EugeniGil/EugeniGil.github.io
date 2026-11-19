---
title: "Using website text to improve counterfactual construction in firm-level policy evaluation"
collection: publications
category: conferences
permalink: /publication/2026-07-01-carma-website-text
excerpt: 'Semantic embeddings of firm website text, added to the covariate set of a Variable Importance Matching procedure, capture strategic characteristics that balance sheets miss and improve the construction of counterfactuals in subsidy evaluation.'
date: 2026-07-01
venue: 'CARMA 2026 — 8th International Conference on Advanced Research Methods and Analytics'
paperurl: 'https://ocs.editorial.upv.es/index.php/CARMA/CARMA2026/paper/view/21942'
citation: 'Gil-Ocana, E., de Pedraza, P., &amp; Garcia-Bernabeu, A. (2026). &quot;Using website text to improve counterfactual construction in firm-level policy evaluation.&quot; In <i>Proceedings of the 8th International Conference on Advanced Research Methods and Analytics (CARMA 2026)</i>, Valencia, 1–3 July 2026. Editorial Universitat Politècnica de València. https://doi.org/10.4995/CARMA2026.2026.21942'
---

Published in the proceedings of **CARMA 2026**, the 8th International Conference on Advanced
Research Methods and Analytics (Valencia, 1–3 July 2026), Editorial Universitat Politècnica de
València (ISSN 2951-9748).

Matching-based evaluation assumes treated and control firms are comparable on all relevant
pre-treatment characteristics, but standard administrative and accounting data describe scale and
sector and say almost nothing about what a firm actually does. We ask whether the text of a firm's
own website can stand in for those unobserved characteristics.

We segment website content, embed each fragment with OpenAI's `text-embedding-3-small` (1,536
dimensions) and mean-pool the fragments into one firm-level vector. Those dimensions then enter
the covariate set of a Variable Importance Matching (VIM) procedure, where a Lasso predicting the
outcome assigns each covariate the weight it carries in a weighted Manhattan distance — so the
match prioritises whatever is actually predictive, financial or semantic.

The illustration links SABI accounts, BDNS subsidy records and website text captured in 2022 for
17,769 Spanish firms (2,552 treated in 2023 under **Kit Digital**, 15,217 controls). Comparing a
financial-only, an embeddings-only and a hybrid specification:

- The hybrid model selects 186 embedding dimensions, which carry **27.66%** of total predictive
  weight — textual information is non-redundant rather than a restatement of the balance sheet.
- Predictive fit is slightly higher for the hybrid specification (*R²* = 0.920) than for financial
  covariates alone (0.916), and far higher than for text alone (0.355).
- All three specifications keep mean standardized differences below the conventional 0.1
  threshold, so the added granularity does not come at the cost of balance.

The pipeline transfers to any firm-level evaluation where unstructured text can proxy for
unobserved characteristics.

## Materials

- [Accepted version, in press (PDF)](/files/carma2026_website_text_matching.pdf)
- [Paper record at Editorial UPV](https://ocs.editorial.upv.es/index.php/CARMA/CARMA2026/paper/view/21942)
- [Conference talk]({{ base_path }}/talks/2026-07-01-carma-website-text)

Assigned DOI: [10.4995/CARMA2026.2026.21942](https://doi.org/10.4995/CARMA2026.2026.21942)
(active once the proceedings volume is released).
