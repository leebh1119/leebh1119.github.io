---
layout: archive
title: "Journal"
permalink: /journal/
author_profile: true
---

{% assign posts = site.journal | sort: "date" | reverse %}

{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}