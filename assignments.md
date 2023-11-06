---
layout: page
title: Assignments
nav_order: 3
description: Listing of course assignments.
---

# Assignments

{% for assignment in site.assignments %}
{{ assignment }}
{% endfor %}
