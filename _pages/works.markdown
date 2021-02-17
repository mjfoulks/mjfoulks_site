---
layout: collection
permalink: "/works/"
title: "Works"
classes: wide
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
<h2>
    <a href="{{ work.url }}"><img src="{{ work.teaser }}" width=250 alt="{{ work.title }}"></a>
  </h2>
</div>
{% endfor %}
