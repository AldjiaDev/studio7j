---
layout: default
title: "Contact — Studio7j"
description: "Une question sur l'offre Studio7j ? Écris-moi directement. Je réponds sous 48h."
permalink: /pages/contact/
---

<div class="contact-page">

  <header class="offer-header">
    <span class="eyebrow">Contact</span>
    <h1 class="h1 offer-header__title">Parlons de<br><em>ton projet.</em></h1>
    <p class="contact-hero__lead">Remplis le formulaire ou écris-moi directement.<br>Je réponds personnellement sous 48h.</p>
  </header>

  <!-- Réassurance -->
  <div class="contact-reassurance">
    <div class="contact-reassurance__item">
      <p class="contact-reassurance__label">Réponse sous 48h</p>
      <p class="contact-reassurance__sub">jours ouvrés</p>
    </div>
    <div class="contact-reassurance__sep" aria-hidden="true"></div>
    <div class="contact-reassurance__item">
      <p class="contact-reassurance__label">Sans engagement</p>
      <p class="contact-reassurance__sub">juste une conversation</p>
    </div>
    <div class="contact-reassurance__sep" aria-hidden="true"></div>
    <div class="contact-reassurance__item">
      <p class="contact-reassurance__label">RDV disponible</p>
      <p class="contact-reassurance__sub">20 min, gratuit</p>
    </div>
  </div>

  <div class="contact-layout">

    <!-- Colonne gauche -->
    <div class="contact-info">

      <p class="contact-info__intro">Tu as un projet en tête, une question sur l'offre, ou tu veux simplement en savoir plus ? Je suis là.</p>

      <div class="contact-info__block">
        <p class="contact-info__label">Email direct</p>
        <a href="mailto:contact.studio7j@gmail.com" class="contact-info__value contact-link">contact.studio7j@gmail.com</a>
      </div>

      <div class="contact-info__block">
        <p class="contact-info__label">Tu préfères un appel ?</p>
        <a href="{{ '/pages/rdv/' | relative_url }}" class="contact-info__cta-link">Réserver un RDV de cadrage →</a>
        <p class="contact-info__note">20 min, gratuit, sans engagement.</p>
      </div>

      <div class="contact-info__block">
        <p class="contact-info__label">On peut parler de</p>
        <ul class="contact-info__list">
          <li>Ton projet de site portfolio</li>
          <li>L'offre et les tarifs</li>
          <li>Une refonte de site existant</li>
          <li>Un partenariat ou une collaboration</li>
        </ul>
      </div>

    </div>

    <!-- Formulaire -->
    <div class="contact-form-wrap">
      <p class="contact-form__heading">Envoie-moi un message</p>
      <form method="POST" action="https://formsubmit.co/contact.studio7j@gmail.com" class="contact-form" novalidate aria-label="Formulaire de contact Studio7j">
        <input type="hidden" name="_next" value="{{ '/pages/merci/' | absolute_url }}" />
        <input type="hidden" name="_subject" value="Nouveau message — Studio7j" />
        <input type="hidden" name="_captcha" value="false" />
        <input type="hidden" name="_template" value="table" />

        <div class="contact-form__row">
          <label class="contact-label" for="contact-name">
            <span>Prénom <abbr title="obligatoire">*</abbr></span>
            <input id="contact-name" name="name" type="text" placeholder="Marie" required aria-required="true" autocomplete="given-name" />
          </label>
          <label class="contact-label" for="contact-email">
            <span>Email <abbr title="obligatoire">*</abbr></span>
            <input id="contact-email" name="email" type="email" placeholder="marie@exemple.fr" required aria-required="true" autocomplete="email" />
          </label>
        </div>

        <label class="contact-label" for="contact-discipline">
          <span>Ta discipline <span class="contact-label__opt">(optionnel)</span></span>
          <input id="contact-discipline" name="discipline" type="text" placeholder="Céramiste, peintre, photographe…" autocomplete="off" />
        </label>

        <label class="contact-label" for="contact-message">
          <span>Ton message <abbr title="obligatoire">*</abbr></span>
          <textarea id="contact-message" name="message" rows="6" placeholder="Dis-moi ce que tu as en tête…" required aria-required="true"></textarea>
        </label>

        <button class="btn btn--lg" type="submit" style="width:100%;justify-content:center">Envoyer le message</button>
        <p class="contact-form__note">Pas d'inscription, pas de newsletter. Juste une réponse.</p>
      </form>
    </div>

  </div>

</div>
