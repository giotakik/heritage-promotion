---
layout: page
title: Λίμνες
permalink: /pois/
---
<p>Οι ομορφότερες φυσικές και τεχνητές λίμνες του μεγαλύτερου σε έκταση νομού της Ελλάδας.</p>
<div class="photos-list">
  {% for p in site.pois %}
    <div class="photos-item">
      <a href="{{ p.url | relative_url }}">
        <img src="{{ p.image | relative_url }}" alt="{{ p.title }}" style="width:100%; max-width: 300px; border-radius: 10px;"/>
        <h3>{{ p.title}}</h3>
      </a>
    </div>
  {% endfor %}
</div>

