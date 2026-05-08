---
layout: default
title: "Déclaration d'accessibilité — Studio7j"
description: "Déclaration d'accessibilité numérique de Studio7j. Niveau de conformité RGAA, technologies utilisées, contacts et démarche d'amélioration."
permalink: /pages/accessibilite/
---

<header class="offer-header">
  <span class="eyebrow">Accessibilité</span>
  <h1 class="h1 offer-header__title">Déclaration<br><em>d'accessibilité.</em></h1>
  <p class="lead offer-header__lead">Dernière mise à jour : mai 2025</p>
</header>

<section class="about-section">
  <div class="prose" style="max-width:72ch">

    <h2>1. État de conformité</h2>
    <p><strong>Studio7j</strong> (www.studio7j.fr) est <strong>conforme</strong> au référentiel général d'amélioration de l'accessibilité (RGAA) version 4.1, niveau AA.</p>
    <p>Les critères suivants sont respectés :</p>
    <ul>
      <li>Lien d'évitement "Aller au contenu principal" présent sur toutes les pages (RGAA 12.7)</li>
      <li>Navigation clavier complète avec indicateurs de focus visibles (RGAA 10.7)</li>
      <li>Page courante identifiée dans la navigation via <code>aria-current="page"</code> (RGAA 12.1)</li>
      <li>Contrastes de couleurs conformes — ratio minimum 4,5:1 pour le texte courant (RGAA 3.2)</li>
      <li>Structure sémantique HTML5 : titres hiérarchisés, landmarks <code>&lt;main&gt;</code>, <code>&lt;nav&gt;</code>, <code>&lt;header&gt;</code>, <code>&lt;footer&gt;</code> (RGAA 9.1)</li>
      <li>Formulaires : labels associés, champs obligatoires signalés, <code>autocomplete</code>, <code>aria-required</code> (RGAA 11.1, 11.10, 11.13)</li>
      <li>Tailles de texte lisibles — minimum 13px, corps 16-18px (RGAA 10.4)</li>
      <li>Vidéo de fond purement décorative, masquée aux technologies d'assistance (<code>aria-hidden="true"</code>) (RGAA 4.2)</li>
      <li>Animations et transitions désactivées si <code>prefers-reduced-motion</code> est activé (RGAA 13.8)</li>
      <li>Fallback textuel et lien alternatif pour l'outil tiers Cal.com (RGAA 2.1)</li>
      <li>Abréviations signalées avec <code>&lt;abbr title&gt;</code> (RGAA 9.4)</li>
    </ul>

    <h2>2. Contenus non accessibles</h2>
    <p>Les contenus suivants restent partiellement dépendants d'outils tiers :</p>
    <ul>
      <li><strong>Intégration Cal.com</strong> (page RDV) — l'accessibilité complète du widget de réservation dépend de Cal.com ; un lien de secours direct est proposé</li>
    </ul>

    <h2>3. Technologies utilisées</h2>
    <ul>
      <li>HTML5</li>
      <li>CSS3 (sans framework)</li>
      <li>JavaScript minimal (chargement différé)</li>
      <li>Jekyll (générateur de site statique)</li>
      <li>GitHub Pages (hébergement)</li>
    </ul>

    <h2>4. Environnements de test</h2>
    <p>Le site a été testé dans les environnements suivants :</p>
    <ul>
      <li>Safari + VoiceOver (macOS)</li>
      <li>Chrome + clavier uniquement (navigation au Tab)</li>
      <li>Firefox sur mobile (iOS Safari)</li>
    </ul>

    <h2>5. Amélioration continue</h2>
    <p>Studio7j s'engage à améliorer progressivement l'accessibilité de ce site. Les points identifiés comme non conformes font l'objet d'un suivi et seront corrigés au fur et à mesure des évolutions du site.</p>

    <h2>6. Contact accessibilité</h2>
    <p>Si vous rencontrez une difficulté d'accès à un contenu ou un service de ce site, vous pouvez nous contacter via le <a href="/pages/contact/">formulaire de contact</a> en précisant :</p>
    <ul>
      <li>La page concernée</li>
      <li>La nature de la difficulté rencontrée</li>
      <li>Votre technologie d'assistance si applicable</li>
    </ul>
    <p>Nous nous engageons à répondre dans un délai de 7 jours ouvrés.</p>

    <h2>7. Voie de recours</h2>
    <p>Si vous n'obtenez pas de réponse satisfaisante, vous pouvez contacter le <strong>Défenseur des droits</strong> :</p>
    <ul>
      <li>En ligne : <a href="https://formulaire.defenseurdesdroits.fr" target="_blank" rel="noopener">formulaire.defenseurdesdroits.fr</a></li>
      <li>Par téléphone : 09 69 39 00 00</li>
      <li>Par courrier : Défenseur des droits — Libre réponse 71120 — 75342 Paris CEDEX 07</li>
    </ul>

  </div>
</section>
