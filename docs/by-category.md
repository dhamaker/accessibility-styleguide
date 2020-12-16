---
title: Patterns by category
layout: page
permalink: /category/
sitemap: false
---
# {{page.title}}

{% for category in sit.categories %}
  {% capture category_name %}{{ category | first }}{% endcapture %}
  <p>{{ category_name }}</p>
{% endfor %}
