---
layout: page
show_meta: false
header:
  title: "Master of Logic"
permalink: "/MoL/"
---

{% assign courses = (site.data.mol | where: "selected", "y") %}
{% for course in courses %}
{% include course.html course=course %}
{% endfor %}
