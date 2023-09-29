---
layout: page
title: Staff
nav_exclude: true
description: A listing of all the course staff members.
---

# Staff

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
