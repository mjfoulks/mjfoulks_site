---
layout: collection
permalink: "/news/"
title: "News"
collection: news
entries_layout: list
classes: wide

---
{% assign sorted = site.resources | reverse %}
{% for item in sorted %}
  <h1>{{ item.name }}</h1>
  <p>{{ item.content }}</p>
{% endfor %}
