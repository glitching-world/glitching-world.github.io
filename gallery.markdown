---
layout: default
title: Gallery
images:
  - image_path: /assets/images/banner.jpeg
    image_link: /assets/images/banner.jpeg
    title: i1
  - image_path: /assets/images/banner.jpeg
    image_link: /assets/images/banner.jpeg
    title: i2
---

<div class="gallery">
  {% for image in page.images %}
  <a href="{{ image.image_link }}">
  <img src="{{ image.image_path }}" alt="{{ image.title}}" />
  </a>
  {% endfor %}
</div>
