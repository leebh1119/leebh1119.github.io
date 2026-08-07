---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

## [Home]({{ base_path }}/)

## [About]({{ base_path }}/about/)

## [Research]({{ base_path }}/research/)

{% assign research_posts = site.research | sort: "date" | reverse %}

{% for post in research_posts %}
- [{{ post.title }}]({{ base_path }}{{ post.url }})
{% endfor %}


## [Performance]({{ base_path }}/performance/)

{% assign performance_posts = site.performance | sort: "date" | reverse %}

{% for post in performance_posts %}
- [{{ post.title }}]({{ base_path }}{{ post.url }})
{% endfor %}


## [Notes]({{ base_path }}/notes/)

{% assign notes_posts = site.notes | sort: "date" | reverse %}

{% for post in notes_posts %}
- [{{ post.title }}]({{ base_path }}{{ post.url }})
{% endfor %}


## [Journal]({{ base_path }}/journal/)

{% assign journal_posts = site.journal | sort: "date" | reverse %}

{% for post in journal_posts %}
- [{{ post.title }}]({{ base_path }}{{ post.url }})
{% endfor %}