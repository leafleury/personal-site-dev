---
layout: post
current: post
cover: assets/images/post-default.jpg
navigation: True
title: Gallery
date: 2018-08-14 17:00:00
tags: [tests]
class: post-template
subclass: 'post'
author: lea
no_menu_item: true
support: [jquery, gallery]
---

# This is a Gallery.


<div id="image-gallery">
{% include gallery-layout.html gallery=site.data.galleries.san-francisco %}
</div>


Something...
