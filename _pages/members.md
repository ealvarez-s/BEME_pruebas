---
layout: default
title: Miembros
permalink: /miembros/
---

<ul>
  {% for member in site.members %}
    <li>
      <a href="{{ member.url }}">
        <img src="{{ member.photo }}" width="100">
        {{ member.name }} – {{ member.role }}
      </a>
    </li>
  {% endfor %}
</ul>