---
layout: archive
title: "Performance"
permalink: /performance/
author_profile: true
---

{% assign posts = site.performance | sort: "date" | reverse %}

{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}