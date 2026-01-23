---
layout: page
title: "Contact"
lead: "Si tu préfères écrire plutôt que réserver un RDV."
permalink: /pages/contact/
---

<form name="contact" method="POST" data-netlify="true" action="/pages/merci/" class="form">
  <input type="hidden" name="form-name" value="contact" />
  <label>Nom <input name="name" required /></label>
  <label>Email <input name="email" type="email" required /></label>
  <label>Message <textarea name="message" rows="6" required></textarea></label>
  <button class="btn" type="submit">Envoyer</button>
</form>
