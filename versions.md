---
title: Versions of the Prosperity Public License
permalink: /versions/index.html
layout: default
---

<ul>
  {% for version in site.versions reversed %}
    <li>
      <a href="{{version.url}}">{{version.number}}</a>
    </li>
  {% endfor %}
</ul>
