--- 
layout:  page
title: Λίμνες
permalink: /pois/
body_class: pois-page
---
<p style="font-style: italic; font-size: 20px; color: darkgreen;">
    Οι ομορφότερες φυσικές και τεχνητές λίμνες του μεγαλύτερου σε έκταση νομού της Ελλάδας.</p>
<div class="image-grid">
  {% for p in site.pois %}
    <div class="photos-item">
      <a href="{{ p.url | relative_url }}">
        <img src="{{ p.image | relative_url }}" alt="{{ p.title }}" style="border-radius: 10px;"/>
        <h3>{{ p.title }}</h3>
      </a>
    </div>
  {% endfor %}
</div>
