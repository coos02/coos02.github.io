---
title: "카테고리 테스트"
layout: archive
permalink: /categories
author_profile: true
sidebar:
  nav: "sidebar-category"
---

{% assign posts = site.categories.blog %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}