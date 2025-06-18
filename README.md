---
layout: page
title: Bioinformatics and Computational Biology
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: BT3117
---

# Bioinformatics and Computational Biology

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
