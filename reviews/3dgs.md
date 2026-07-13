---
title: "3D Gaussian Splatting"
permalink: /reviews/3dgs/
layout: archive
author_profile: true
sidebar:
  nav: "paper-sidebar"
---

둥둥둥

{% assign category_posts = site.categories["3DGS"] %}

{% if category_posts.size > 0 %}
  {% for post in category_posts %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
아직 등록된 3DGS 게시글이 없습니다.
{% endif %}
