# Dia : vocabulaire

Vous êtes invité à faire des pulls requests pour mettre à jour le vocabulaire.

## Technologies

* **HTML5** (HyperText Markup Language) : Langage de description de la structure d'une page web. Interprété par les navigateurs web pour afficher les données contenues. HTML ne fait que donner la structure des pages (ceci est un titre), il faut le coupler avec CSS (Cascading StyleSheet) pour personnaliser l'affichage (je veux que mes titres soient en gras, rouge, souligné).
* **Javascript** : Langage de programmation, historiquement uniquement interprété par le navigateur pour rendre dynamique l'affichage des pages web (faire apparaître/disparaître un élément par exemple).
* **Node.js** : Les gens qui développaient en Javascript se sont dit que ça pourrait être intéressant de développer des applications complètes avec un même langage : ainsi est né Node.js. Node.js est un interpréteur de Javscript côté serveur. Il permet de faire tout ce à quoi on s'attend de sa part : génération de pages HTML, communication avec une base de données, ...
* **Nginx** : Serveur web. Un serveur web est un logiciel qui écoute sur les ports d'un serveur (généralement 80 pour HTTP et 443 pour HTTPS) et qui gère les requêtes des clients et les réponses à leur renvoyer. Il est capable de servir des fichiers statiques (souvent `.css` et `.js`) ou bien de transférer des requêtes à une application qu'on aurait écrite. Par exemple si je développe une application en Node.js hébergée sur le serveur `facebook.com`, l'appel à l'adresse `https://www.facebook.com/settings` sera très probablement traité par Node.js (page à générer dynamiquement en fonction de mes réglages personnels), mais l'appel à `https://www.facebook.com/style.css` ne devrait pas atteindre mon serveur Node, elle sera traitée par Nginx qui ira chercher le fichier `style.css` et le servira à mon navigateur.
* **ØMQ** :
* **PostgreSQL** : Serveur de base de données **relationnelles** libre. Capable de stocker des lignes contenues dans des tables contenues dans des bases de données. On peut appliquer des contraintes sur certaines données, par exemple dire qu'une colonne de ma table fait référence à une autre colonne d'une autre table, ou encore une contrainte d'unicité sur une colonne (tous les éléments doivent être uniques).
* **MongoDB** : Serveur de base de données **NoSQL** libre. Au contraire de PostgreSQL, MongoDB ne stocke pas les données sous une forme aussi structurée. On stocke les données sous forme de documents contenus dans des collections. Les documents prennent la forme d'objets JSON et ne contiennent pas nécessairement tous les mêmes clés, même au sein d'une même collection.
* **Angular / React / Vue.js** : Framework Javascript frontend.

## Processus et méthodes

* Réplication :
* Statique :
* API :
* Versioning :
* Passage à l'échelle :

## Vocabualaire métiers

* **Back-office** : On en parle souvent pour les sites marchands. C'est l'interface réservée au(x) gérant(s) du site : gestion des stocks, des commandes, des paiements, etc.
* **Architecture** : Ensemble du frontend, du backend et de tout ce qui fait communiquer les deux.
* **Frontend** : Partie "client" de l'architecture.
* **Backend** : Partie "serveur" de l'architecture.
