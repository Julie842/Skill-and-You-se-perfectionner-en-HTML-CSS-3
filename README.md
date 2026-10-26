# Skill-and-You-se-perfectionner-en-HTML-CSS-3

Exercice : créer un site vitrine de quatre pages

Ce projet est un site web front-end vitrine conçu en HTML5 et CSS3. L'objectif est d'offrir une navigation simple et élégante à travers différentes pages pour présenter les activités de la librairie et recommander des lectures aux visiteurs.

🌟 Fonctionnalités principales :
Navigation multi-pages : accès rapide aux différentes sections (accueil, présentation, coups de cœur, extraits choisis).
Navigation par ancres : sous-menu permettant d'accéder directement aux catégories (classiques, romans) dans la page des coups de cœur.
Présentation des ouvrages : mise en page en cartes (.book-card) regroupant le titre, l'auteur, l'année et le genre.
Affichage des horaires : liste claire des heures d'ouverture pour chaque jour de la semaine.
Blocs de citations : mise en valeur d'aphorismes et d'extraits littéraires philosophiques (Nietzsche, Montaigne, Machiavel).

🛠️ Technologies utilisées :
HTML5 : structuration sémantique du contenu (<header>, <nav>, <main>, <article>, <footer>, etc.).
CSS3 :
Variables CSS (:root) pour la gestion centralisée de la charte graphique.
Layout Flexbox pour le centrage du menu, des cartes de livres et du pied de page.
Stylisation typographique (ombrages de texte, polices personnalisées).
Ciblage pseudo-classe :target pour l'interaction avec les ancres.

🎨 Charte graphique :
Couleur primaire : rouge bordeaux (#aa3322 et #721717)
Couleurs secondaires : nuances de gris (#cccccc, #aaaaaa, #ededed)
Largeur fixe du conteneur : 960px centré (margin: 0 auto)

📂 Structure du projet :
├── index.html            # Page d'accueil
├── presentation.html     # Page de présentation et horaires
├── coups-de-coeur.html   # Sélection et cartes de livres
├── extraits-choisis.html # Citations et aphorismes
├── style.css             # Feuille de style globale
└── img/                  # Ressources visuelles
    ├── favicon.png
    └── bandeau.jpg
