---
layout: default
title: Gallery
images:
  - image_path: /assets/images/banner.jpeg
    title: i1
  - image_path: /assets/images/banner.jpeg
    title: i2
---

<ul class="gallery">
  {% for image in page.images %}
  <img src="{{ image.image_path }}" alt="{{ image.title}}" />
  {% endfor %}
</ul>
