---
layout: default
title: Projects
images:
  - image_path: /assets/images/res_banner.jpg
    image_link: /jekyll/update/2020/10/08/Resolutions-and-Aspect-Ratios-Cheat-Sheet.html
    title: Resolutions and Aspect Ratios Cheat Sheet
---

<div class="gallery">
  {% for image in page.images %}
  <a href="{{ image.image_link }}">
  <img src="{{ image.image_path }}" alt="{{ image.title}}" />
  <blockquote>{{ image.title }}</blockquote>
  </a>
  {% endfor %}
</div>
