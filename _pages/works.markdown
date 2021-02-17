---
layout: collection
permalink: "/works/"
title: "Works"
classes: wide
entries_layout: list
show_excerpts: false
#gallery:
#  - url: /works/loa_toter/
#    image_path: /assets/images/loa-toter-teaser.jpg
#    alt: loa-toter-teaser
#    title: Tales from the Elvish Realms
#  - url: /works/loa_affs/
#    image_path: /assets/images/loa-affs-teaser.jpg
#    title: A Frightful First Step
#    url: /works/loa_affs
---

## The Legends of Akelian Series:
<div class="row">
{% for work in site.works %}
  <a href="{{ work.url }}"><img src="{{ work.teaser }}" width=200 alt="{{ work.title }}"></a>
</div>
{% endfor %}}
