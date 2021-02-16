---
layout: collection
permalink: "/news/"
title: "News"
entries_layout: list
classes: wide
---
{% assign sorted = site.news | sort: 'date' | reverse %}
{% for item in sorted %}
<h2><a href="{{ item.url }}">{{ item.title }}</a></h2>
{% endfor %}
