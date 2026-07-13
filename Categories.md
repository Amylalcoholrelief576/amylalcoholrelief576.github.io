---
layout: default
title: Categories
permalink: /categories/
---

# Categories

{% for category in site.categories %}
## {{ category[0] }}

{% for post in category[1] %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}

{% endfor %}
