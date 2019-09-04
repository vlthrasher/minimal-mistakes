---
layout: single
title: "Work Experience"
permalink: /work/
---

{% include base_path %}


<div class="grid__wrapper">
  {% assign reverse_work = site.work | reverse %}
  {% for post in reverse_work %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
