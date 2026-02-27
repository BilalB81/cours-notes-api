# API Notes Markdown

## Description
Cette application est une API Node.js permettant d’exposer des notes de cours écrites en Markdown.

Chaque fichier `.md` placé dans le dossier `notes/` devient automatiquement accessible via une route de l’API.

## Technologies utilisées
- Node.js
- Express
- Marked
- Git & GitHub

## Lancer le projet

Installer les dépendances :

npm install

Démarrer le serveur :

node server.js

## Routes disponibles

- `/` → Vérification API
- `/notes` → Liste des notes
- `/notes/:slug` → Affichage d’une note
Déclenchement du workflow CI.