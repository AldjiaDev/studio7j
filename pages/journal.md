---
layout: page
title: "Journal"
lead: "Conseils concrets pour créer un portfolio d’artiste efficace."
permalink: /journal/
---

<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> — <span class="small">{{ post.date | date: "%d/%m/%Y" }}</span></li>
  {% endfor %}
</ul>
