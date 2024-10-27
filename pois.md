---
layout: page
title: Λίμνες
permalink: /pois/
---

<div class="photos-list">
  {% for p in site.pois %}
    <div class="photos-item">
      <a href="{{ p.url | relative_url }}">
        <!-- Εικόνα της λίμνης -->
        <img src="{{ p.image }}" alt="{{ p.title }}" style="width:100%; max-width: 300px; border-radius: 10px;"/>
        <!-- Τίτλος και περιγραφή της λίμνης -->
        <h3>{{ p.title }}</h3>
        <p>{{ p.description }}</p>
      </a>
    </div>
  {% endfor %}
</div>

