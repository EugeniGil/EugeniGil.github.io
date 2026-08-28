---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% if site.author.googlescholar %}
You can also find my articles on <a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.
{% endif %}

{% for category in site.publication_category %}
{% assign posts_in_category = site.publications | where: "category", category[0] %}
{% if posts_in_category.size > 0 %}
## {{ category[1].title }}

{% assign ordered = posts_in_category | sort: "date" | reverse %}
{% for post in ordered %}
{% include archive-single.html %}
{% endfor %}
{% endif %}
{% endfor %}
