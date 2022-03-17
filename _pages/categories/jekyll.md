---
layout: archive
permalink: jekyll
title: "Jekyll"
published: true
author_profile: false
sidebar:
  nav: "docs"
---

{% assign posts = site.categories.jekyll %}
{% for post in posts %}
  {% include archive-single.html type=entries_layout %}
{% endfor %}