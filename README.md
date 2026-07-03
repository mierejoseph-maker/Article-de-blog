Article de blog — HTML5 sémantique

Page d'article de blog statique construite en HTML5 sémantique pur, sans aucun CSS. Le projet sert de démonstration/gabarit pour une structure de blog complète : article, catégories, tags, tableau de données, commentaires et formulaire.

Contenu du repo

.
├── article-blog.html   # Page unique contenant tout le projet
└── README.md            # Ce fichier

Il n'y a qu'un seul fichier HTML autonome : aucune dépendance externe, aucun build, aucun framework.

Utilisation

Ouvrir la page directement

Aucune installation n'est nécessaire.


Téléchargez article-blog.html.
Double-cliquez dessus, ou ouvrez-le depuis votre navigateur via Fichier > Ouvrir.
Structure de la page

Le fichier article-blog.html est organisé selon la sémantique HTML5 suivante :

SectionBaliseContenuMenu principal<header><nav>Liens de navigation du siteArticle<article>Titre, auteur, date, catégorie, corps de texteImages<figure><figcaption>Deux illustrations légendéesCitation<blockquote><cite>Citation attribuée avec sourceDonnées<table>Tableau de résultats avec <caption>, <thead>, <tbody>Commentaires<section><ol><article>Liste de commentaires, avec une réponse imbriquéeFormulaire<form><fieldset>Formulaire de dépôt de commentaireSidebar<aside><nav>Articles récents et liste des catégoriesPied de page<footer><nav>Liens légaux et flux RSS
