---
layout: collection
permalink: "/news/"
title: "News"
entries_layout: list
classes: wide
---
{% assign sorted = site.news | sort: 'date' | reverse %}
{% for item in sorted %}
<li>{{ item.title }}</li>
{% endfor %}
