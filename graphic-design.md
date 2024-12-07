---
title: Graphic Design Portfolio
---

<ul>
  {% for item in site.graphic-design %}
    <li>
      <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
      <span> - {{ item.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>