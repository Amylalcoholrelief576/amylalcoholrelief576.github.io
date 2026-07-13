---
title: "3D Gaussian Splatting"
permalink: /reviews/3dgs/
layout: archive
author_profile: false
sidebar:
  nav: "paper-sidebar"
---

3D Gaussian Splatting의 기본 원리, 확장 연구, 압축, 재구성 및 의료영상 적용 논문을 정리합니다.

{% assign category_posts = site.categories["3DGS"] %}

{% if category_posts.size > 0 %}
  {% for post in category_posts %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
아직 등록된 3DGS 게시글이 없습니다.
{% endif %}
