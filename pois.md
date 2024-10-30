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
        <h3>{{ p.title}}</h3>
         <p> Εξερευνώντας τις ομορφότερες φυσικές και τεχνητές λίμνες του μεγαλύτερου σε έκταση νομού της Ελλάδας μέσα από αυτόν τον ιστότοπο.</p>
      </a>
    </div>
  {% endfor %}
</div>

