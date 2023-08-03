---
title: Kasa
publishDate: 2023-06-30 00:00:00
img: /assets/projects/kasa-home.webp
img_alt: La page d'accueil du projet Kasa
description: |
   Il s'agissait de réaliser le front end d'une appli de location chez l'habitant
tags:
   - React
   - JS
   - CSS/Sass
---

### Description

L'idée du projet est de travailler a intégrer la maquette d'un site de location de chambre chez l'habitant. Il fallait utiliser React avec Create React App, React Router et aucune autre bibliothèque. A des fins d'apprentissage, et comme cela était permis, j'ai décidé de faire le style du site avec Sass. Le projet se compose d'une page d'accueil, d'une page produit, d'une page "à propos" et d'une page d'erreur.

### Difficultés rencontrées / Compétences acquises

L'un des principaux problèmes a été de comprendre la logique de React et l'utilisation des props pour passer correctement les données d'une page à une autre. Un problème qui fut réglé en conjuguant la documentation de React et celle de React Router. Ce dernier offrant des outils de routing et de chargement des données permettant non seulement de pré charger les données d'une page quand le lien qui y mène est affiché, mais également de gérer l'affichage des composants "erreur" quand les paramètres de l'url ne sont pas bons, entre autres. Le tout permettant d'exploiter la logique de composant réutilisable en y injectant les données appropriées.
L'élaboration d'un carousel a également été un peu fastidieuse mais finalement rapidement réglée.

Au final, ce projet m'a permis de comprendre la logique structurelle d'un environnement comme React et d'en saisir les fondations. Il m'a aussi permis d'approfondir ma connaissance en JavaScript ainsi que d'appréhender Sass, même si les fonctionnalités les plus communes de ce préprocesseur commencent à être intégrées de manière native au CSS, le rendant moins important dans l'usage que j'en fais pour l'instant.

### Code & Screenshots

<a href="https://github.com/AntoinePigny/OC-Projet6-KasaReact">Le Code</a>

![Page produit Kasa](/assets/projects/kasa-product.webp 'Kasa Location')

![Page à propos Kasa](/assets/projects/kasa-about.webp 'Kasa A propos')
