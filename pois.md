--- 
layout:  page
title: Λίμνες
permalink: /pois/
---
<p style="font-style: italic; font-size: 20px; color: darkgreen;">
    Οι ομορφότερες φυσικές και τεχνητές λίμνες του μεγαλύτερου σε έκταση νομού της Ελλάδας.</p>
<div class="image-grid"style="background-color: #accbe1; color: #333;">
  {% for p in site.pois %}
    <div class="photos-item">
      <a href="{{ p.url | relative_url }}">
        <img src="{{ p.image | relative_url }}" alt="{{ p.title }}" style="border-radius: 10px;"/>
        <h3>{{ p.title }}</h3>
      </a>
    </div>
  {% endfor %}
</div>
