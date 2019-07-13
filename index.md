---
title: Index
template: default
---

# {{page.title}}

<ul>
  {% for pages in site.pages %}
    <li>
      <a href="{{ pages.url | relative_url }}">{{ pages.title }}</a>
    </li>
  {% endfor %}
</ul>

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
