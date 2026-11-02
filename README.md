# Portfolio de Thomas – Graphiste freelance

Site vitrine responsive « BeThom » (HTML5 / CSS3, JavaScript minimal pour le menu mobile), intégré par AgencEco d’après la maquette Figma.

## Police utilisée
**Heebo** (Google Fonts), avec repli sur Poppins puis Arial.

## Structure
```
index.html
css/style.css
js/main.js
assets/img/   images (SVG provisoires) + favicon
assets/docs/  cv-thomas.pdf (à remplacer par le vrai CV)
```

## Installation
Aucune dépendance : ouvrir `index.html` dans un navigateur, ou lancer `python3 -m http.server` à la racine du projet.

## Déploiement (serveur mutualisé)
Envoyer tout le contenu du dossier à la racine du site (`www/` ou `public_html/`) par FTP ou via le gestionnaire de fichiers.

## Points d'attention
- Ancres : `#accueil`, `#articles`, `#portfolio`, `#contact` (formulaire de contact).
- Points de rupture : desktop au-dessus de 992 px, tablette jusqu'à 992 px, mobile jusqu'à 768 px.
- Couleurs centralisées dans les variables CSS (`:root`).
- Valider avec https://validator.w3.org et https://jigsaw.w3.org/css-validator/.
