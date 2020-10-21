---
layout: default
title: Projects
author: António Costa
description: A kind of gallery for my projects.
permalink: /projects/
images:
  - image_path: /assets/images/noise_banner.jpg
    image_link: /jekyll/update/2020/10/13/NOISE.html
    title: NOISE - My computer sees things in weird way.
---

<div class="gallery">
  {% for image in page.images %}
  <a href="{{ image.image_link }}">
  <img src="{{ image.image_path }}" alt="{{ image.title}}" />
  <blockquote>{{ image.title }}</blockquote>
  </a>
  {% endfor %}
</div>
