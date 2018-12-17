---
layout: page
show_meta: false
header:
  title: "Bachelor AI"
permalink: "/BKI/"
---



{% assign courses = (site.data.bki | where: "selected", "y") %}
{% for course in courses %}
{% include course.html course=course %}
{% endfor %}
