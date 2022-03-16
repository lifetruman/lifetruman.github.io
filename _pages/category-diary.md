---
title: "DIARY"
layout: archive
permalink: diary
author_profile: false
sidebar_main: true
sidebar:
    nav: "docs"
---

{% assign posts = site.categories.diary %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}