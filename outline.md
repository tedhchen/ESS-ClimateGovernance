---
layout: page
title: Outline
nav_order: 2
description: Listing of course modules and topics.
---
# Course Outline

The course outline is subject to change to adapt to contingencies that may arise. Changes to due dates are unlikely, but in the event they occur, students will be given ample notice.

## Weekly Schedule

{% assign outline = site.modules | where: 'type', 'outline' %}
{% for module in outline %}
{{ module }}
{% endfor %}
