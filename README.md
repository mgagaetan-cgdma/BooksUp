BOOKS UP — Présentation et vision du projet
Books UP — dossier de conception
1. Idée générale
Books UP est une plateforme web qui rassemble plusieurs livres dans une seule interface. Un visiteur peut découvrir les livres, consulter leurs informations, rechercher un titre, ouvrir une fiche détaillée et, lorsque le téléchargement est autorisé, télécharger le fichier.
2. Objectifs
•	Centraliser une bibliothèque numérique dans un site simple et moderne.
•	Permettre une recherche rapide par titre, auteur, catégorie ou mot-clé.
•	Présenter une fiche détaillée pour chaque livre.
•	Permettre le téléchargement des livres lorsque leur diffusion est légalement autorisée.
•	Prévoir une architecture facile à agrandir avec de nouveaux livres et de nouvelles catégories.
•	Prévoir plus tard un espace administrateur pour ajouter, modifier ou retirer des livres.
3. Fonctionnalités proposées
•	Accueil avec livres récents, populaires et catégories.
•	Catalogue avec cartes de livres.
•	Recherche instantanée.
•	Filtres par catégorie.
•	Page détail d'un livre.
•	Bouton Lire en ligne lorsque le format le permet.
•	Bouton Télécharger pour les fichiers dont la diffusion est autorisée.
•	Système de favoris local.
•	Responsive design pour téléphone, tablette et ordinateur.
•	Administration future : ajout de livres, catégories, auteurs, couvertures et fichiers.
4. Structure recommandée
•	frontend/ : interface utilisateur.
•	assets/ : images, icônes et styles.
•	books/ : fichiers de livres autorisés à la distribution.
•	data/ : catalogue JSON au démarrage.
•	admin/ : futur espace de gestion.
•	backend/ : future API et base de données.
5. Attention aux droits
Books App doit uniquement proposer des livres que l'on a le droit de distribuer : œuvres du domaine public, livres dont l'auteur ou l'éditeur a donné l'autorisation, ou contenus créés par l'équipe du projet. Un livre protégé par le droit d'auteur ne doit pas être mis en téléchargement sans autorisation.
