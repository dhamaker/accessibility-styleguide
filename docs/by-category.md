---
title: Patterns by category 3
layout: page
permalink: /category/
sitemap: false
---
# {{page.title}}

{% for category in sit.categories %}
  <p>{{ category[0] }}</p>
{% endfor %}
