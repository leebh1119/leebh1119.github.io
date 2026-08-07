---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% assign posts = site.research | sort: "date" | reverse %}

{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}
