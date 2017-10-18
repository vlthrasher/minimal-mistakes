---
layout: single
title: Work Experience
permalink: /work/
---

{% include base_path %}


<div class="grid__wrapper">
  {% for post in site.work %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
