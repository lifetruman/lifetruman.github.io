---
layout: archive #default
permalink: defaul #원하는 카테고리
title: "Default" #카테고리 제목

author_profile: false #프로필 유, 무
sidebar:
  nav: "docs" #default ,docs말고 다르게 할 경우에만 건드리기
---
<!-- #default -->
{% assign posts = site.categories.toyproject %}
{% for post in posts %}
  {% include archive-single.html type=entries_layout %}
{% endfor %}