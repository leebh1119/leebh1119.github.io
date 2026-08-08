---
layout: splash
title: "Flexibility, Resilience, and Termination"
permalink: /

header:
  overlay_image: home.png
  overlay_filter: 0.45
---

<div class="splash-hero-text">
  Trade everything that has data.
</div>

<a id="content-start"></a>

### Flexibility, Resilience, and Termination

Exploring quantitative trading and financial markets.

---

## Latest Updates

{% assign all_posts = site.research
  | concat: site.performance
  | concat: site.notes
  | concat: site.journal
%}

{% assign all_posts = all_posts | sort: "date" | reverse %}

{% for post in all_posts limit:5 %}

### [{{ post.title }}]({{ post.url | relative_url }})

{{ post.excerpt | strip_html | truncate: 160 }}

{% endfor %}