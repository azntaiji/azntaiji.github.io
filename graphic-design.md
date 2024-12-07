---
title: Graphic Design Portfolio
modified: 2024-12-06
---

<ul>
  {% for item in site.graphicdesign %}
    <li>
      <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
      <span> - {{ item.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>