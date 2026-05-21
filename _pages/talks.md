---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

{% if site.talkmap_link == true %}

<a href="{{ base_path }}/talkmap.html">See a map of all the places I've given a talk!</a>

{% endif %}

{% include base_path %}

{% assign ordered_talks = site.talks | sort:"date" | reverse %}
{% for post in ordered_talks %}
  {% include archive-single-talk.html %}
{% endfor %}
