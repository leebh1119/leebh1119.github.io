---
layout: splash
title: "Flexibility, Resilience, and Termination"
permalink: /

header:
  overlay_image: home.png
  overlay_filter: 0.45
---

### Flexibility, Resilience, and Termination

퀀트 트레이딩과 금융시장을 연구하고 기록합니다.

---

## Latest Posts

{% for post in site.posts limit:5 %}

### [{{ post.title }}]({{ post.url }})

{{ post.excerpt | strip_html | truncate: 160 }}

{% endfor %}