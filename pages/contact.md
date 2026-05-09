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
  </header>

  <div class="contact-simple">

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
    </form>

    <div class="contact-simple__footer">
      <p>Tu préfères un appel ? <a href="{{ '/pages/rdv/' | relative_url }}" class="contact-link">Réserver un RDV gratuit →</a></p>
      <p>Ou par email : <a href="mailto:contact.studio7j@gmail.com" class="contact-link">contact.studio7j@gmail.com</a></p>
    </div>

  </div>

</div>
