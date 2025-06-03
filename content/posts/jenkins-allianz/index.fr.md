---
title: "Réalisation : Modernisation des pipelines Jenkins chez Allianz Technology"
date: 2025-03-08T08:06:25+06:00
menu:
  sidebar:
    name: Modernisation des Pipelines Jenkins
    identifier: jekins
    weight: 32
---
# 

# Modernisation des pipelines Jenkins chez Allianz Technology

## Un Contexte en Pleine Transformation
Je travaille au sein d'Allianz Technology France, sur le projet Midcorp, ce projet consiste à développer un site pour créer des contrats d’assurance pour les entreprises de taille moyenne. Ce projet est développé par dix équipes de développement, chacune se concentrant sur un domaine spécifique. Mon équipe, l'équipe 7, se concentre sur le domaine géographique. Elle se charge principalement de l’évaluation des risques pour un lieu donné, par exemple la probabilité d’avoir un tremblement de terre ou des inondations. Ceci permet d’aider au calcul du prix du contrat d’assurance. Moi je travaille principalement sur le microservice geo-risk, c’est un des nombreux microservices du projet. Mais durant la première phase du projet nous avons découvert un problème majeur, chaque microservice utilisait un script de configuration différent pour la pipeline Jenkins. Cela signifie que si nous voulions apporter des modifications, nous devrions les appliquer à chaque script individuellement, ce qui serait fastidieux et risqué en termes d'erreurs potentielles.
J’avais donc pour objectif de développer un script qui pourrait être réutilisé dans tous les microservices du projet, on appelle ça une bibliothèque Jenkins partagée.

## Une Bibliothèque Jenkins Partagée
Pour le projet Midcorp, j'ai créé une bibliothèque commune Jenkins afin de standardiser et de simplifier les pipelines Jenkins utilisés par les diverses équipes. Une bibliothèque commune Jenkins permet de réutiliser du code et des fonctionnalités similaires dans différents pipelines Jenkins différents. Il s'agit principalement d'un ensemble de scripts, de fonctions et de méthodes stockés dans un référentiel à jour, qui peuvent être appelés et réutilisés à différentes étapes des pipelines Jenkins.

## Les Risques
Les principaux risques identifiés étaient causés par la résistance au changement liée au fait que tous les scripts de tous les microservices devaient être mis à jour par les différentes équipes, ce qui les fait perdre du temps. Sur le plan personnel, il y avait le défi de créer une librairie qui devait être facile à utiliser mais aussi qui puisse s’adapter aux besoins de toutes les équipes du projet.

## Le Chemin Parcouru
J'ai commencé par analyser les besoins des différentes équipes et évaluer les pratiques actuelles en matière de pipelines Jenkins. Ensuite, j'ai conçu et développé la Shared Library Jenkins, en veillant à ce qu'elle soit flexible et adaptable aux besoins spécifiques de chaque équipe. J'ai également coordonné avec les autres membres de l'équipe pour assurer une adoption réussie de la bibliothèque partagée. J’ai dû contacter chaque personne de chaque équipe qui avait la charge de la gestion du script Jenkins de leur équipe et leur présenter la nouvelle alternative.

## Un Succès Collectif et Individuel
La Shared Library Jenkins a été largement adoptée par les dix équipes du projet Midcorp, entraînant une amélioration significative de l'efficacité des processus de développement, grâce à l’uniformisation des différents pipelines. Les retours des différentes équipes ont été très positifs, soulignant la facilité d'utilisation de la bibliothèque partagée.

## Lendemains du projet
À court terme, je prévois d'ouvrir la contribution à la Shared Library Jenkins à d'autres membres des différentes équipes, favorisant ainsi l'innovation collaborative. À long terme, je souhaite présenter cette initiative à d'autres projets au sein d'Allianz Technology, afin de partager les meilleures pratiques et les leçons apprises.

## Une Collaboration Élargie et des Horizons Nouveaux
Je suis fier d'avoir mené à bien ce projet, démontrant ma capacité à initier des initiatives d'amélioration et à collaborer efficacement avec les autres membres de l'équipe. J'ai appris l'importance de la communication et de la collaboration dans la réussite d'un projet, ainsi que la valeur de l'innovation et de l'adaptabilité dans un environnement en constante évolution. Pour le futur, je m'engage à continuer à chercher des opportunités d'amélioration et à partager mes connaissances et expériences avec mes collègues.
