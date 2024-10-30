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
        <h3>{{ p.title }}</h3>
         <p style="font-size: 22px; max-width: 600px; text-align: justify;">Περιηγηθείτε στις ενότητες και ανακαλύψτε τις ομορφότερες λίμνες του μεγαλύτερου σε έκταση νομού της Ελλάδας! Μέσα από τον ιστότοπό μας, μπορείτε να μάθετε για τα μοναδικά τοπία, τις δραστηριότητες και τις εμπειρίες που προσφέρει η κάθε περιοχή.</p>
      </a>
    </div>
  {% endfor %}
</div>

