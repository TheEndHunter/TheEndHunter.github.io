---
layout: default
title: Authors
description: list of authors
---

{% for author in site.authors %}
  <h2>
    <a href="{{ author.url }}">
      {{ author.title }}
    </a>
  </h2>
  <p>{{ staff_member.description | markdownify }}</p>
{% endfor %}