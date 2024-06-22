# Projet DéClic - Borne de Commande

Bienvenue dans le projet DéClic, une application web développée avec Angular pour le front-end (`declic-front`) et Nest.js pour le back-end (`declic-back`). Cette application vise à fournir une interface intuitive pour permettre aux utilisateurs de passer des commandes facilement via une borne de commande.

## Fonctionnalités
- Interface Utilisateur Intuitive : Une interface conviviale pour naviguer et commander des produits.
- Gestion des Commandes : Système complet pour sélectionner, personnaliser et finaliser les commandes.
- Authentification Utilisateur : Fonctionnalités d'inscription et de connexion pour les utilisateurs.
- Administration des Produits : Gestion des produits disponibles à la commande.

## Prérequis
Avant de commencer, assurez-vous d'avoir installé les outils suivants :

- Node.js et npm : Pour exécuter les scripts et gérer les packages.
- Angular CLI : Outil en ligne de commande pour Angular.
- Nest CLI : Outil en ligne de commande pour Nest.js.

## Installation
### Cloner le Répertoire

```bash
git clone https://github.com/votre-utilisateur/declic-borne-commande.git
cd declic-borne-commande
Installer les Dépendances
Pour le front-end (declic-front) :

bash
Copier le code
cd declic-front
npm install
Pour le back-end (declic-back) :

bash
Copier le code
cd declic-back
npm install
Configuration de l'Environnement
Pour Angular (declic-front) :
Configurez votre environnement dans declic-front/src/environments/environment.ts.

Pour Nest.js (declic-back) :
Configurez les variables d'environnement dans declic-back/.env en suivant declic-back/.env.example.

Démarrage
Démarrer le Serveur Angular
bash
Copier le code
cd declic-front
ng serve
L'application front-end sera accessible à l'adresse http://localhost:4200.

Démarrer le Serveur Nest.js
bash
Copier le code
cd declic-back
npm run start:dev
Le serveur Nest.js démarrera et écoutera par défaut sur http://localhost:3000.

Contribution
Pour contribuer à ce projet, suivez ces étapes :

Fork du projet.
Créez une branche pour votre fonctionnalité (git checkout -b feature/NouvelleFonctionnalite).
Committez vos changements (git commit -am 'Ajout de NouvelleFonctionnalite').
Pushez vers la branche (git push origin feature/NouvelleFonctionnalite).
Créez une nouvelle Pull Request.
Licence
Ce projet est sous licence MIT. Consultez le fichier LICENSE pour plus d'informations.