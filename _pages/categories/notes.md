---
layout: archive
permalink: notes
title: "Notes"
published: true
author_profile: false
sidebar:
  nav: "docs"
---

{% assign posts = site.categories.notes %}
{% for post in posts %}
  {% include archive-single.html type=entries_layout %}
{% endfor %}