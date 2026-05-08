# Charte Graphique — Studio7j

> La référence des sites pour artistes et artisans.
> Rendu galerie. Livraison en 7 jours.

---

## Positionnement de marque

Studio7j s'adresse aux artistes et artisans qui veulent un site professionnel sans perdre leur temps. Le design incarne ce positionnement : **galerie d'art + studio de création + promesse de rapidité**.

Le site doit inspirer confiance immédiatement — si Studio7j ne ressemble pas lui-même à un excellent site d'artiste, personne ne lui confiera le sien.

---

## Palette de couleurs

| Token           | Valeur      | Usage                            |
|-----------------|-------------|----------------------------------|
| `--cream`       | `#F7F4EF`   | Fond principal (mur de galerie)  |
| `--cream-warm`  | `#EDE8DF`   | Fond secondaire, survol          |
| `--white`       | `#FFFFFF`   | Cards, formulaires               |
| `--ink`         | `#1A1714`   | Texte principal (noir chaud)     |
| `--stone`       | `#7A746C`   | Texte secondaire, légendes       |
| `--sand`        | `#DDD7CE`   | Bordures, séparations            |
| `--ochre`       | `#C96B2D`   | Accent principal (terra cotta)   |
| `--ochre-dark`  | `#A85523`   | Hover sur ochre                  |

**Principe :** le fond crème (pas blanc pur) évoque le papier, la toile, les murs d'une galerie. L'ochre (orange terre) rappelle les pigments, l'atelier, la matière. Le noir est chaud, jamais froid.

---

## Typographie

### Cormorant Garamond — Display / Titres
Police des grandes galeries et maisons de luxe culturel. Élégante, légèrement contrastée, très lisible en grand. Utilisée pour tous les titres (`h1`, `h2`, `h3`) et le nom du studio dans le footer.

- Italic sur les accents émotionnels (ex : *comme une galerie*)
- Weights : 300 (light), 400 (regular), 500 (medium)
- Letter-spacing : légèrement négatif en grand (`-0.025em`)

### DM Sans — Interface / Corps
Claire, moderne, optimisée pour les écrans. Utilisée pour le corps de texte, la navigation, les boutons, les labels.

- Weights : 300 (light), 400 (regular), 500 (medium)
- Letter-spacing : légèrement positif sur les petits éléments uppercase

### Règle de combinaison
- Titre de section : Cormorant Garamond 400
- Eyebrow label : DM Sans 400, uppercase, letter-spacing 0.20em, couleur ochre
- Corps : DM Sans 300
- CTA/bouton : DM Sans 400

---

## Logo

```
Studio 7j
------
"Studio" : DM Sans 300, uppercase, letter-spacing 0.20em, 12px
"7j"     : Cormorant Garamond italic 400, 20px, couleur ochre (#C96B2D)
Tagline  : DM Sans 300, 10px, stone
```

Le contraste DM Sans (rationnel, moderne) + Cormorant italic (sensible, artistique) encode la promesse de la marque : professionnel ET artiste.

---

## Espacement

Base : **4px**. Tous les espacements sont des multiples de 4.

| Token   | Valeur |
|---------|--------|
| `--s1`  | 4px    |
| `--s2`  | 8px    |
| `--s3`  | 12px   |
| `--s4`  | 16px   |
| `--s5`  | 20px   |
| `--s6`  | 24px   |
| `--s8`  | 32px   |
| `--s10` | 40px   |
| `--s12` | 48px   |
| `--s16` | 64px   |
| `--s20` | 80px   |
| `--s24` | 96px   |

**Sections :** padding vertical généreux (`var(--s16)` = 64px) — l'espace est une valeur, comme dans une galerie.

---

## Composants

### Boutons
- **Primary** : fond ochre, texte blanc, border-radius 4px (pas pill — plus editorial)
- **Ghost** : transparent, bordure sand → ink au hover

### Cards
- Grille à joints fins (1px gap sur fond sand) — style musée/galerie
- Fond blanc, hover cream
- Numérotation optionnelle en Cormorant léger

### Header
- Position sticky avec backdrop-filter blur(14px)
- Hauteur 68px desktop, 60px mobile
- Sur mobile : seul le CTA reste visible dans la nav

### Footer
- Fond ink (noir chaud) — contraste fort, haut de gamme
- Nom du studio en Cormorant italic, crème

---

## Voix de la marque

- **Tu** (pas vous) — on s'adresse à des créateurs, pas à des DRH
- Phrases courtes, directes
- Aucune promesse floue — tout est mesurable (7 jours, 20 minutes, 1 vague de retours)
- Ton calme et confiant, jamais vendeur agressif

---

## Ce qui doit rester invariant

1. Le fond n'est jamais blanc pur (`#F7F4EF`, pas `#FFFFFF`)
2. L'ochre ne s'utilise que sur les CTA et eyebrows — pas en fond de section
3. Cormorant Garamond en italic uniquement sur les accents émotionnels, pas sur les titres principaux
4. Les bordures sont toujours `var(--sand)` — jamais grises froides
5. La nav cache les liens secondaires sur mobile — le CTA reste toujours visible
