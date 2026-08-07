---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

## Home

- [Home]({{ base_path }}/)

## About

- [About]({{ base_path }}/about/)

## Research

- [Research]({{ base_path }}/research/)

{% assign research_posts = site.research | sort: "date" | reverse %}

{% for post in research_posts %}
  - [{{ post.title }}]({{ base_path }}{{ post.url }})
{% endfor %}

## Performance

- [Performance]({{ base_path }}/performance/)

{% assign performance_posts = site.performance | sort: "date" | reverse %}

{% for post in performance_posts %}
  - [{{ post.title }}]({{ base_path }}{{ post.url }})
{% endfor %}

## Notes

- [Notes]({{ base_path }}/notes/)

{% assign notes_posts = site.notes | sort: "date" | reverse %}

{% for post in notes_posts %}
  - [{{ post.title }}]({{ base_path }}{{ post.url }})
{% endfor %}

## Journal

- [Journal]({{ base_path }}/journal/)

{% assign journal_posts = site.journal | sort: "date" | reverse %}

{% for post in journal_posts %}
  - [{{ post.title }}]({{ base_path }}{{ post.url }})
{% endfor %}