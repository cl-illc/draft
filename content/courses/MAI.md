---
layout: page
show_meta: false
header:
  title: "MSc AI"
permalink: "/MAI/"
---


{% assign courses = (site.data.mai | where: "selected", "y") %}
{% for course in courses %}
{% include course.html course=course %}
{% endfor %}
