---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- You can also link a PDF version of your CV here:
[Download CV (PDF)](/files/cv.pdf) -->

Education
======
* Ph.D. in Social Sciences and Economics, Universitat Politècnica de València (UPV), 2026–2030 *(expected)*
* M.Sc. in Data Science and Big Data applied to Finance, Afi Global Education, 2023
* M.Sc. in Economic Development and Economic Growth, Universidad Carlos III de Madrid, 2021
  * Master's thesis: *Financial Fragility in Spain: a liquidity approach*
* B.Sc. in Business Administration and Management, University of Mount Olive (USA), 2016
  * Graduated *Cum Laude* in three years (GPA 3.71/4). Cross Country and Track athlete on scholarship.

Work experience
======
* **Jan 2026 – present: Predoctoral Researcher**
  * Universitat Politècnica de València (UPV)
  * Public policy evaluation within the EVALIAX project, combining causal inference with explainable AI (XAI).

* **Jun 2023 – Jan 2026: Data Scientist**
  * Vocento
  * Built and deployed machine learning models in production for subscription propensity, churn, and user classification.
  * Engineered large-scale datasets in a distributed environment using SQL, Hive, Python, R, PySpark, and Scala.
  * Developed applications on AWS (EMR, EC2, SageMaker, Redshift, Glue, Lambda, Athena, S3) and built ETL pipelines with automated data validation.
  * Applied clustering, time-series analysis, and NLP to deliver analytics use cases across business areas.

* **Jul 2022 – Jun 2023: Data Scientist**
  * Universidad Alfonso X el Sabio
  * Developed end-to-end ML solutions to improve student performance and reduce dropout rates.
  * Built dashboards and KPIs in Power BI and supported the automation of internal university processes (Python, SQL, Git, MS Power Automate).

* **Sep 2021 – Jun 2022: Data Analyst, Public Policy Evaluation**
  * Autoridad Independiente de Responsabilidad Fiscal (AIReF)
  * Evaluated public policies using advanced statistical and econometric methods; co-authored ad hoc project reports.
  * Projects on financial instruments and communications costs (Stata, MS Excel, Power BI).

* **Jan 2018 – Dec 2019: Professional Trail Runner**
  * Original Buff, S.A.
  * Member of the Buff Pro Team.

Skills
======
* Programming and data
  * Python, R, SQL, Scala, PySpark, Hive, Stata
* Machine learning and econometrics
  * Causal inference, explainable AI (XAI), time-series analysis, clustering, NLP, panel data
* Cloud and tools
  * AWS (EMR, EC2, SageMaker, Redshift, Glue, Lambda, Athena, S3), Git, Power BI
* Languages
  * [EDIT: e.g. Spanish (native), English (C1)]

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
