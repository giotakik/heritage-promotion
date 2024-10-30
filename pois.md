---
layout: page
title: Λίμνες
permalink: /pois/
---

<div class="photos-list">
  {% for p in site.pois %}
    <div class="photos-item">
      <a href="{{ p.url | relative_url }}">
        <img src="{{ p.image | relative_url }}" alt="{{ p.title }}" style="width:100%; max-width: 300px; border-radius: 10px;"/>
        <p><em>Κάθε λίμνη έχει τη δική της μοναδική ομορφιά όπως και τα δικά της μοναδικά events και δραστηριότητες!.</em></p>
        <h3>{{ p.title }}</h3>
        <p>{{ p.description }}</p>
      </a>
    </div>
  {% endfor %}
</div>
