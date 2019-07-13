---
title: Index
template: default
---

# {{page.title}}

<ul>
  {% for page in site.pages %}
    <li>
      <a href="{{ page.url | relative_url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
</ul>

## Patterns
<ul>
  {% for pattern in site.patterns %}
    <li>
      <a href="{{ pattern.url | relative_url }}">{{ pattern.title }}</a>
    </li>
  {% endfor %}
</ul>

## Categories
{% for category in site.categories %}
  <h3>{{ category[0] }}</h3>
  <ul>
    {% for pattern in category[1] %}
      <li><a href="{{ pattern.url }}">{{ pattern.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
