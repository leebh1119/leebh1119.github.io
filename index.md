---
layout: splash
title: 
permalink: /

header:
  overlay_image: home1.png
  overlay_filter: 0.45
---

### Data · Research · Markets

퀀트 트레이딩과 금융시장을 연구하고 기록합니다.

---

## Research

퀀트 트레이딩 전략을 연구합니다.

Momentum, Mean Reversion, Factor Investing, ETF Rotation 등을 중심으로 전략을 설계하고 백테스트합니다.

[Research →](/research/)

---

## Performance

전략의 백테스트와 성과를 기록합니다.

CAGR, MDD, Sharpe Ratio 등의 지표를 통해 전략을 분석합니다.

[Performance →](/performance/)

---

## Notes

논문, 기사, 책 등 시장과 투자에 관한 자료를 읽고 정리합니다.

[Notes →](/notes/)

---

## Journal

시장에 대한 생각과 투자 아이디어를 기록합니다.

[Journal →](/journal/)

---

## Latest Posts

{% for post in site.posts limit:5 %}

### [{{ post.title }}]({{ post.url }})

{{ post.excerpt | strip_html | truncate: 160 }}

{% endfor %}