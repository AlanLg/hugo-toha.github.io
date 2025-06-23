---
title: "Réalisation : Space Monopoly"
date: 2025-03-08T08:06:25+06:00
menu:
  sidebar:
    name: Space Monopoly
    identifier: monopoly
    parent: realisations
    weight: 31
---

Durant mon troisième semestre d'études, j'ai participé à la création de Space Monopoly, un projet de groupe ambitieux qui consistait à réinventer le classique jeu du Monopoly dans un univers de science-fiction, le tout en 3D. L'objectif était de développer un jeu complet où les joueurs naviguent sur un plateau intergalactique, achètent des planètes et construisent des stations pour asseoir leur domination.

Nous étions une équipe de quatre, et nous nous sommes organisés avec Trello pour la répartition des tâches. Ayant déjà de bonnes bases en Java, je me suis naturellement concentré sur le back-end, c'est-à-dire la logique centrale du jeu : la gestion des tours, les transactions entre joueurs, les propriétés, etc.

Le projet était rythmé par des démonstrations toutes les deux semaines devant notre professeur, ce qui nous a permis d'avoir un cadre de travail itératif et de recevoir des retours réguliers pour améliorer notre jeu pas à pas.

## Mes Contributions et les Technologies Employées

Le projet nous imposait d'utiliser Java pour la logique et JavaFX pour l'interface graphique et la 3D. Contrairement à d'autres membres de l'équipe pour qui Java était une découverte, mon défi n'était pas d'apprendre le langage, mais plutôt de l'appliquer de la manière la plus propre possible dans une architecture Modèle-Vue-Contrôleur (MVC).

Mon rôle principal a été de concevoir et d'implémenter le "moteur" du jeu. Cela impliquait de créer des classes robustes pour gérer les joueurs, le plateau, les cartes et les propriétés, en s'assurant que toute la logique soit indépendante de l'affichage 3D.

Une de mes contributions dont je suis particulièrement fier a été de débloquer un de mes coéquipiers. Il était chargé des animations 3D dans JavaFX mais rencontrait des difficultés pour les faire s'exécuter dans le bon ordre, ce qui causait des bugs visuels. Pour l'aider, j'ai développé un petit système de gestion de file d'attente pour les animations. Ce système permettait de lancer les animations les unes après les autres de manière contrôlée, ce qui a résolu le problème et a rendu le jeu beaucoup plus fluide et agréable visuellement.

## Les Défis Techniques que nous avons Relevés

Comme pour tout projet, nous avons fait face à plusieurs défis. Le principal était la gestion de l'état du jeu. Sans base de données, toutes les informations (position des joueurs, argent, propriétés) étaient stockées en mémoire. Il fallait donc être très rigoureux pour s'assurer que chaque action d'un joueur mette à jour correctement toutes les données sans créer d'incohérences.

Un autre défi, partagé par toute l'équipe, était la performance au démarrage du jeu. Le chargement initial de tous les modèles 3D et des textures causait un petit temps de latence avant que l'application ne soit parfaitement fluide.

## Un Résultat dont nous étions Fiers

Au final, le jeu était une grande réussite. Il était fonctionnel, stable, et nous étions tous très fiers de voir le résultat de nos efforts prendre vie en 3D. Les règles du Monopoly étaient bien respectées et l'expérience de jeu était amusante.

Le moment qui a validé tout notre travail a été notre victoire au TechDay de l'école. Voir notre projet classé premier parmi toutes les promotions a été une immense satisfaction et la récompense de mois de travail acharné.

Avec du recul, je vois bien sûr des axes d'amélioration. Nous aurions pu mieux structurer certaines parties de notre code pour éviter un peu de redondance, et une meilleure gestion du chargement des ressources graphiques aurait pu éliminer le temps de latence au démarrage.

## Ce que ce Projet m'a Apporté

Space Monopoly a été une expérience extrêmement formatrice. Pour moi, ce projet n'était pas une introduction à la programmation orientée objet, mais plutôt une occasion d'approfondir ma compréhension de l'architecture logicielle et des design patterns comme le MVC.

J'y ai appris l'importance de concevoir un back-end solide et découplé de l'interface utilisateur, et j'ai aussi renforcé mes compétences en travail d'équipe et en résolution de problèmes, notamment en aidant mes coéquipiers sur des points techniques.

Ce projet a confirmé mon intérêt pour l'architecture logicielle et m'a donné une grande confiance pour aborder des projets encore plus complexes par la suite. C'est une des expériences fondatrices de mon parcours de développeur.
