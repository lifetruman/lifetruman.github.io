---
layout: archive
permalink: portfolio
title: "Portfolio"
published: true
author_profile: false
sidebar:
  nav: "docs"
---

{% assign posts = site.categories.portfolio %}
{% for post in posts %}
  {% include archive-single.html type=entries_layout %}
{% endfor %}