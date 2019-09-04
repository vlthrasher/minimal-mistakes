---
layout: single
title: "Projects"
permalink: /projects/
---

{% include base_path %}


<div class="grid__wrapper">
  {% assign reversed_projects = site.projects | reverse %}
  {% for post in reversed_projects %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>




