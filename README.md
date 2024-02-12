# ChillTimes
Développer une application Android permettant à un utilisateur de découvrir et chercher des comics, séries et films.


Application Comics Flutter
Introduction
Cette application Android est conçue pour permettre aux utilisateurs de découvrir et rechercher des comics, des séries et des films. Utilisant l'API ComicVine de Gamespot, elle offre une riche base de données accessible sans nécessiter de backend propre.

Fonctionnalités
Pour tous les groupes
Écran d'accueil: Affiche les dernières actualités, séries, comics et films.
Liste des séries: Permet de parcourir une liste de séries.
Détail d'une série: Affiche des détails sur une série spécifique, y compris l'histoire, les personnages et les épisodes.
Exclusives aux groupes de 3
Liste des comics: Navigation à travers une liste de comics.
Détails d'un comics: Montre des détails sur un comic spécifique, incluant l'histoire, les auteurs et les personnages.
Recherche: Fonctionnalité de recherche sur les comics, films et séries.
Bonus (non obligatoire)
Liste des films: Visualisation d'une liste de films.
Détails d'un film: Informations détaillées sur un film spécifique, y compris le synopsis, les personnages et les données de production.
API
Utilise l'API ComicVine de Gamespot pour toutes les données sauf les actualités. Les appels sont limités à 200 par heure.

Développement
Environnement Requis
Android SDK avec support pour Android >= 7 (API 24).
Flutter SDK pour le développement d'applications cross-platform.
Installation
Clonez le dépôt Git : git clone [URL_DU_REPO]
Ouvrez le projet dans votre IDE préféré.
Installez les dépendances Flutter : flutter pub get
Lancez l'application sur un émulateur ou un appareil réel.
Structure du Projet
lib/: Contient le code source Dart de l'application.
assets/: Ressources graphiques et de design utilisées dans l'application.
Design
Le design utilise les couleurs suivantes :

Arrière-plan des écrans: #15232E
Orange: #FF8100
Plus de détails disponibles dans le fichier de design partagé.
Contribution
Pour contribuer au projet, veuillez suivre les instructions suivantes :

Fork le projet
Créez votre branche de fonctionnalité (git checkout -b feature/AmazingFeature)
Commit vos changements (git commit -m 'Add some AmazingFeature')
Push vers la branche (git push origin feature/AmazingFeature)
Ouvrez une Pull Request
