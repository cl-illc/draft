---
layout: page
show_meta: false
header: no
permalink: "/reading/"
---


{% assign groups = (site.data.reading | where: "selected", "y") %}
{% for group in groups %}
{% include group.html group=group %}
{% endfor %}
