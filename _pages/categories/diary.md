---
layout: archive
permalink: diary
title: "Diary"
published: true
author_profile: false
sidebar:
  nav: "docs"
---

{% assign posts = site.categories.diary %}
{% for post in posts %}
  {% include archive-single.html type=entries_layout %}
{% endfor %}