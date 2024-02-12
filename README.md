# ChillTimes
Développer une application Android permettant à un utilisateur de découvrir et chercher des comics, séries et films.

<h1>Application Comics Flutter</h1>

<h2>Introduction</h2>
<p>Cette application Android est conçue pour permettre aux utilisateurs de découvrir et rechercher des comics, des séries et des films. Utilisant l'API ComicVine de Gamespot, elle offre une riche base de données accessible sans nécessiter de backend propre.</p>

<h2>Fonctionnalités</h2>
<h3>Pour tous les groupes</h3>
<ul>
    <li><strong>Écran d'accueil</strong>: Affiche les dernières actualités, séries, comics et films.</li>
    <li><strong>Liste des séries</strong>: Permet de parcourir une liste de séries.</li>
    <li><strong>Détail d'une série</strong>: Affiche des détails sur une série spécifique, y compris l'histoire, les personnages et les épisodes.</li>
</ul>

<h3>Exclusives aux groupes de 3</h3>
<ul>
    <li><strong>Liste des comics</strong>: Navigation à travers une liste de comics.</li>
    <li><strong>Détails d'un comics</strong>: Montre des détails sur un comic spécifique, incluant l'histoire, les auteurs et les personnages.</li>
    <li><strong>Recherche</strong>: Fonctionnalité de recherche sur les comics, films et séries.</li>
</ul>

<h3>Bonus (non obligatoire)</h3>
<ul>
    <li><strong>Liste des films</strong>: Visualisation d'une liste de films.</li>
    <li><strong>Détails d'un film</strong>: Informations détaillées sur un film spécifique, y compris le synopsis, les personnages et les données de production.</li>
</ul>

<h2>API</h2>
<p>Utilise l'API ComicVine de Gamespot pour toutes les données sauf les actualités. Les appels sont limités à 200 par heure.</p>

<h2>Développement</h2>
<h3>Environnement Requis</h3>
<ul>
    <li>Android SDK avec support pour Android >= 7 (API 24).</li>
    <li>Flutter SDK pour le développement d'applications cross-platform.</li>
</ul>

<h3>Installation</h3>
<ol>
    <li>Clonez le dépôt Git : <span class="code">git clone [URL_DU_REPO]</span></li>
    <li>Ouvrez le projet dans votre IDE préféré.</li>
    <li>Installez les dépendances Flutter : <span class="code">flutter pub get</span></li>
    <li>Lancez l'application sur un émulateur ou un appareil réel.</li>
</ol>

<h3>Structure du Projet</h3>
<ul>
    <li><strong>lib/</strong>: Contient le code source Dart de l'application.</li>
    <li><strong>assets/</strong>: Ressources graphiques et de design utilisées dans l'application.</li>
</ul>

<h2>Design</h2>
<p>Le design utilise les couleurs suivantes :</p>
<ul>
    <li>Arrière-plan des écrans: <span class="code">#15232E</span></li>
    <li>Orange: <span class="orange">#FF8100</span></li>
    <li>Arrière-plan des cartes : #1E3243</li>
    <li>Arrière-plan d'un élément dans une carte : #284C6A</li>
    <li>Arrière-plan de "Voir plus" : #0F1921</li>
    <li>Arrière-plan bottom bar : #0F1E2B</li>
    <li>Arrière-plan bottom bar - sélectionné : #12273C</li>
    <li>Texte bottom bar - sélectionné : #12273C</li>
    <li>Texte bottom bar - non sélectionné : #778BA8</li>

</ul>
<p>Plus de détails disponibles dans le fichier de design partagé.</p>

<h2>Contribution</h2>
<p>Pour contribuer au projet, veuillez suivre les instructions suivantes :</p>
<ol>
    <li>Fork le projet</li>
    <li>Créez votre branche de fonctionnalité (<span class="code">git checkout -b feature/AmazingFeature</span>)</li>
    <li>Commit vos changements (<span class="code">git commit -m 'Add some AmazingFeature'</span>)</li>
    <li>Push vers la branche (<span class="code">git push origin feature/AmazingFeature</span>)</li>
    <li>Ouvrez une Pull Request</li>
</ol>
