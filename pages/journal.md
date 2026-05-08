---
layout: default
title: "Journal Studio7j"
description: "Conseils, méthodes et ressources pour créer un site d'artiste qui travaille vraiment pour toi."
permalink: /pages/journal/
---

<div class="blog-header">
  <span class="eyebrow">Journal</span>
  <h1 class="h1">Ressources pour<br><em>les créateurs.</em></h1>
  <p class="lead">Conseils concrets pour créer un site d'artiste qui te ressemble — et qui te trouve des clients.</p>
</div>

<div class="blog-grid">
  {% for post in site.posts %}
  <article class="blog-card">
    <a class="blog-card__link" href="{{ post.url | relative_url }}">
      <div class="blog-card__meta">
        <span class="blog-card__date">{{ post.date | date: "%d %b %Y" }}</span>
        {% if post.reading_time %}<span class="blog-card__sep">·</span><span class="blog-card__time">{{ post.reading_time }} min de lecture</span>{% endif %}
      </div>
      <h2 class="blog-card__title">{{ post.title }}</h2>
      {% if post.excerpt %}<p class="blog-card__excerpt">{{ post.excerpt | strip_html | truncatewords: 22 }}</p>{% endif %}
      <span class="blog-card__cta">Lire l'article <span aria-hidden="true">→</span></span>
    </a>
  </article>
  {% else %}
  <p class="muted">Les premiers articles arrivent bientôt.</p>
  {% endfor %}
</div>

<div class="section--cta" style="margin-top:var(--s16)">
  <span class="eyebrow">Tu veux un site ?</span>
  <h2 class="h2">On commence par un RDV.</h2>
  <p class="lead">20 minutes pour clarifier ton projet. Gratuit, sans engagement.</p>
  {% include cta-rdv.html %}
</div>
