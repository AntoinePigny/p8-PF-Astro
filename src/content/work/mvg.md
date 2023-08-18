---
title: MVG | Mon Vieux Grimoire
publishDate: 2023-07-16 00:00:00
img: /assets/projects/mvg-home.webp
img_alt: La page d'accueil du projet MVG
description: |
   Créer le Back-end d'une application de notation de livres
tags:
   - NodeJS
   - Express
   - MongoDB/Mongoose
   - Sharp
---

### Description

Ici, il a fallu, à partir d'un front-end livré (React), créer le back d'un site de notations de livres.

-  Base de données MongoDB
-  Environnement Node
-  API express
-  Sauvegarde des images sur disque dur, après redimensionnement pour respecter les pratiques de Green Code (Sharp)

L'application devait permettre une authentification utilisateur et afficher un contenu dynamique, soumis à un JWT stocké en en-tête de requête.

### Difficultés rencontrées / Compétences acquises

L'appréhension d'un environnement Node et l'élaboration de la logique de chaque endpoint de l'api a constitué la principale difficulté de ce projet. En particulier la gestion des erreurs et des cas particuliers. J'ai eu l'aide de plusieurs ressources sur le sujet (documentations officielles, tutoriels) et des retours d'un évaluateur Openclassrooms, ce qui m'a permis de mieux gérer les mots de passes (hachage, salage), la validation des données et la protection contre les requêtes type "brute force", ou les injections nosql.

Tout ce projet m'a donnée une vue d'ensemble de l'élaboration d'un back-end simple mais solide, et m'a tout particulièrement challengé sur la prise en charge des cas particuliers ou des erreurs, et m'a forcé à essayer de me représenter une multitude de cas de figures, en dehors du simple cadre de la bonne fonctionnalité des requêtes.

### Code & Screenshots

<a target="_blank" href="https://github.com/AntoinePigny/OC-Projet7-MonVieuxGrimoire-Backend">Le Code</a>

![Page produit Kasa](/assets/projects/mvg-auth.webp 'Kasa Location')
