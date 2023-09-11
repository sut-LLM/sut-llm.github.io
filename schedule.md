---
layout: page
title: Schedule
nav_order: 6
description: The weekly event schedule.
---

# Google Calendar

<iframe src="https://calendar.google.com/calendar/embed?src=fc884cac707b61f05fff6d59ee9649631392dc7db347531781e1c97ca7daea2a%40group.calendar.google.com&ctz=Asia%2FTehran" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>

# Weekly Schedule

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
