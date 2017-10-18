---
layout: single
title: Projects
permalink: /projects/
---

<div class="grid_wrapper">
  {% for post in site.posts %}
      {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
