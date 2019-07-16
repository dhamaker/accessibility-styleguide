---
title: Patterns by category
layout: page
permalink: /category/
sitemap: false
---
<h1>{{page.title}}</h1>

{% assign categories = site.categories %}
{% for category in categories %}
{{ category }}
{% endfor %}
