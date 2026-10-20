# Portfolio - Nathan Mourat

Site statique : une seule page `index.html` (HTML, CSS, JavaScript), servie par GitHub Pages.

- Animations : GSAP 3.12.5 + ScrollTrigger (CDN cdnjs). Sans GSAP, ou avec « réduire les animations » activé, tout le contenu reste affiché sans animation.
- Polices : Archivo (titres, axe de largeur animé), IBM Plex Sans et IBM Plex Mono (Google Fonts).
- Schéma PV + stockage du haut de page : SVG animé en JavaScript, curseur d'ensoleillement (démo illustrative, P ≈ Pc × G / 1000).
- Bilingue FR / EN : chaque texte traduit porte un attribut `data-en`.

## Formulaire de contact

Le formulaire passe par [FormSubmit](https://formsubmit.co) (aucun compte nécessaire).

1. Après la mise en ligne, envoyer un premier message de test depuis le site.
2. FormSubmit envoie un e-mail « Activate Form » à nathanmourat6@gmail.com : cliquer sur le lien.
3. Les messages suivants arrivent directement dans la boîte Gmail (réponse possible avec « Répondre »).

Tant que le formulaire n'est pas activé, le site affiche un message d'erreur avec un lien e-mail de secours.

## Mise en ligne sur GitHub Pages

Settings > Pages > Source : branche `main`, dossier `/ (root)`. Le site est servi sur https://nathanmourat.github.io.

## Fichiers

- `index.html` : page complète (structure, styles, script)
- `*.jpg` : photos des projets, à la racine
- `.nojekyll` : désactive le traitement Jekyll de GitHub Pages
