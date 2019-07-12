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

## Categories
{% for category in site.categories %}
  <h3>{{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
