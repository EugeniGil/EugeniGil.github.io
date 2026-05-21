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
* Ph.D in [EDIT Field], [EDIT University], [EDIT Year] *(expected)*
* M.S. in [EDIT Field], [EDIT University], [EDIT Year]
* B.S. in [EDIT Field], [EDIT University], [EDIT Year]

Work experience
======
* **[EDIT Start – End]: [EDIT Job Title]**
  * [EDIT Institution / Company]
  * Duties included: [EDIT brief description]
  * Supervisor: [EDIT Name]

* **[EDIT Start – End]: [EDIT Job Title]**
  * [EDIT Institution / Company]
  * Duties included: [EDIT brief description]

Skills
======
* [EDIT skill category 1]
  * [EDIT sub-skill 1.1]
  * [EDIT sub-skill 1.2]
* [EDIT skill category 2]
* [EDIT skill category 3]

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

Service and leadership
======
* [EDIT] e.g. Reviewer for [Journal / Conference], [Year]
* [EDIT] e.g. Organizer of [Event], [Year]
* [EDIT] e.g. Member of [Society / Committee]
