---
layout: default
title: Eduardo Antonio - Portfolio
permalink: /projects/
---
<div class="gallery">
<div class="gallery-container">
    <div class="title">
    </div>
    <div class="project-gallery">
      {% for project in site.projects %}
        <div class="gallery-item">
          <a href="{{ project.url | relative_url }}">
            <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
            <p>{{ project.title}}</p>
          </a>
        </div>
      {% endfor %}
    </div>

</div>
</div>
