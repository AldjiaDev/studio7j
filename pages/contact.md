---
layout: default
title: "Contact — Studio7j"
description: "Une question sur l'offre Studio7j ? Écris-moi directement. Je réponds sous 48h."
permalink: /pages/contact/
---

<div class="contact-page">

  <header class="offer-header">
    <span class="eyebrow">Contact</span>
    <h1 class="h1 offer-header__title">Une question ?<br><em>Écris-moi.</em></h1>
  </header>

  <div class="contact-layout">

    <!-- Colonne gauche : infos -->
    <div class="contact-info">
      <div class="contact-info__block">
        <p class="contact-info__label">Délai de réponse</p>
        <p class="contact-info__value">Sous 48h, jours ouvrés.</p>
      </div>
      <div class="contact-info__block">
        <p class="contact-info__label">Tu préfères un appel ?</p>
        <p class="contact-info__value">
          <a href="{{ '/pages/rdv/' | relative_url }}" class="contact-link">
            Réserver un RDV de cadrage →
          </a>
        </p>
        <p class="contact-info__note">20 min, gratuit, sans engagement.</p>
      </div>
      <div class="contact-info__block">
        <p class="contact-info__label">Pour quoi écrire ?</p>
        <ul class="contact-info__list">
          <li>Une question sur l'offre</li>
          <li>Un projet particulier à discuter</li>
          <li>Un partenariat ou une collaboration</li>
        </ul>
      </div>
    </div>

    <!-- Colonne droite : formulaire -->
    <div class="contact-form-wrap">
      <form name="contact" method="POST" data-netlify="true" action="{{ '/pages/merci/' | relative_url }}" class="contact-form">
        <input type="hidden" name="form-name" value="contact" />

        <label class="contact-label">
          <span>Ton prénom</span>
          <input name="name" type="text" placeholder="Marie" required />
        </label>

        <label class="contact-label">
          <span>Ton email</span>
          <input name="email" type="email" placeholder="marie@exemple.fr" required />
        </label>

        <label class="contact-label">
          <span>Ta discipline <span class="contact-label__opt">(optionnel)</span></span>
          <input name="discipline" type="text" placeholder="Céramiste, peintre, photographe…" />
        </label>

        <label class="contact-label">
          <span>Ton message</span>
          <textarea name="message" rows="5" placeholder="Dis-moi ce que tu as en tête…" required></textarea>
        </label>

        <button class="btn btn--lg" type="submit" style="width:100%;justify-content:center">Envoyer le message</button>
        <p class="contact-form__note">Pas d'inscription, pas de newsletter. Juste une réponse.</p>
      </form>
    </div>

  </div>

</div>
