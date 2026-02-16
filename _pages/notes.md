---
layout: archive
title: "Notes"
permalink: /notes/
---

{% for post in site.notes %}
  {% include archive-single.html type="list" %}
{% endfor %}