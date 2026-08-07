---
layout: archive
title: "Notes"
permalink: /notes/
author_profile: true
---

{% assign posts = site.notes | sort: "date" | reverse %}

{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}