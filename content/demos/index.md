---
layout: page
show_meta: false
header:
  title: "Demos"
permalink: "/demos/"
---

{% assign groups = (site.data.demos | where: "selected", "y") %}
{% for group in groups %}  

  {% include group.html group=group %}

{% endfor %}
