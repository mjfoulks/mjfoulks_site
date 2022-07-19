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

## Legends Of Akelian

[![image-left](/assets/images/loa-toter-teaser.jpg){: .align-left}](https://www.mjfoulks.com/works/loa_toter)
[![image-left](/assets/images/loa-affs-teaser.jpg){: .align-left}](https://www.mjfoulks.com/works/loa_affs)

## Other Works
[![image-left](/assets/images/innocent-cover-sm.png){: .align-left}](https://www.mjfoulks.com/works/lti_)

<div class="row">
{% assign sorted = site.works | sort: 'date' %} 
{% for work in sorted %}
<a href="{{ work.url }}"><img src="{{ work.teaser }}" width=200 alt="{{ work.title }}"></a>
{% endfor %}
</div> 
