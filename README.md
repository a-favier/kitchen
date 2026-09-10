# Cuisine — documents techniques

Page de suivi du projet de cuisine : matériaux EGGER, plans, appareils commandés et achats encore en cours.

Ouvrir `index.html` dans un navigateur. Les PDF du dossier doivent rester à côté de la page.

## Version

**1.3.2** — affichée en bas de page.

## Écran d’accueil

Au chargement, un écran « Salut Jo ! » s’affiche, puis le bouton **Consulter la cuisine**.

Pour le désactiver, une seule ligne dans le `<head>` de `index.html` :

```js
window.KITCHEN_SHOW_INTRO = true;
```

- `true` : afficher l’intro
- `false` : ouvrir directement la page cuisine

## Matériaux

- **Plan de travail** — EGGER H3157 ST12, Chêne Vicenza, Omnipore Matt  
  https://www.egger.com/fr/mobilier-agencement-interieur/decors/H3157_12?country=FR
- **Façades** — EGGER U604 ST9, Vert eucalyptus, Smoothtouch Matt  
  https://www.egger.com/fr/mobilier-agencement-interieur/decors/U604_9?country=FR

Les teintes à l’écran sont indicatives. EGGER recommande un échantillon réel avant fabrication.

## Plans

Section prévue, fichiers pas encore ajoutés :

- Implantation (vue de dessus et cotes)
- Élévations (vues des meubles)

## Appareils commandés

- Beko BSSA315K4SN — réfrigérateur
- Beko BMGB25333BG — micro-ondes
- Rosières RO6 T3B3EYTB — four
- Hotpoint HI5030WEF — lave-vaisselle
- Electrolux EIV66453I — plaque à induction

Le dossier menuisier est `Dossier_technique_menuisier.pdf`.

## Achats en cours

Pas encore de modèle choisi :

- évier (à encastrer dans le plan Chêne Vicenza)
- robinet
- hotte (au-dessus de la plaque Electrolux)

## Page web

- thème clair uniquement
- recherche (`/` pour focus)
- navigation vers matériaux, plans et appareils
