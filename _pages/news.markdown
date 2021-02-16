---
layout: collection
permalink: "/news/"
title: "News"
entries_layout: list
classes: wide
---
{% assign sorted = site.news | sort: 'date' | reverse %}
{% for item in sorted %}
<h3><a href="{{ item.url }}">{{ item.title }}</a></h3>
<small><i>"{{ item.date | date: "%B %d, %Y" }}"</i></small>
{% endfor %}
