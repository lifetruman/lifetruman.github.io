---
layout: archive
permalink: toyproject
title: "Toy Project"

author_profile: false
sidebar:
  nav: "docs"
---

{% assign posts = site.categories.toyproject %}
{% for post in posts %}
  {% include archive-single.html type=entries_layout %}
{% endfor %}