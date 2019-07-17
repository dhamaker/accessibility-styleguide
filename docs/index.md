---
title: Index
layout: default
---

# {{page.title}}

{% assign pages = site.pages | where: "layout", "page" %}
<ul>
  {% for page in pages  %}
    <li>
      <a href="{{ page.url | relative_url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
</ul>

## Patterns
{% assign patterns = site.pages | where: "layout", "pattern" %}
<ul>
  {% for page in patterns  %}
    <li>
      <a href="{{ page.url | relative_url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
</ul>

### Navigation
{% assign patterns = site.pages | where: "categories", "navigation" %}
<ul>
  {% for page in patterns  %}
    <li>
      <a href="{{ page.url | relative_url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
</ul>
