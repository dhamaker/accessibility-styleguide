---
title: Accessibiltiy Style Guideline
template: default
---
#{{page.title}}
<h2>Index</h2>
<ul>
  {% for pages in site.pages %}
    <li>
      <a href="{{ pages.url | relative_url }}">{{ pages.title }}</a>
    </li>
  {% endfor %}
</ul>
