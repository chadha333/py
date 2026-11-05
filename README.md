# TP – Publier et synchroniser un projet Python

## Présentation

Ce projet est le TP1 de l'unité Outils collaboratifs (Licence 1)
Le programme main.py est un petit « assistant de révision » : il pose
quelques questions à l'utilisateur et affiche un message personnalisé
L'objectif du TP est de s'entraîner avec Git et GitHub

## Versions V1 à V4

Le fichier main.py a évolué en quatre versions successives :

- V1 : message de bienvenue, créé sur mon PC.
- V2 : ajout du prénom de l'utilisateur, puis premier git push vers GitHub
- V3 : ajout de la matière à réviser, modifiée directement sur GitHub,
  puis récupérée sur mon PC avec git pull.
- V4 : ajout de la durée de révision sur mon PC, puis nouveau git push

## Comment exécuter le programme

Outils nécessaires : Python et Visual Studio Code.

1. Ouvrir le dossier du projet dans VS Code, puis cliquer sur main.py.
2. Cliquer sur le bouton ▶ **Run Python File** en haut à droite.
   Si nécessaire, choisir l'interpréteur Python.
3. Dans le terminal intégré, saisir le prénom, la matière et la durée
   en minutes. Valider chaque réponse avec Entrée.

## Commandes Git utilisées

 git init : crée un dépôt Git dans le dossier
- git add : prépare les fichiers modifiés pour le commit
- git commit: enregistre une version avec un message
- git push: envoie mes commits vers GitHub
- git pull : récupère les commits de GitHub sur mon PC