---
title: "Réalisation : Un clone de Twitter"
date: 2025-03-08T08:06:25+06:00
menu:
sidebar:
name: Clone de Twitter
identifier: fastlink
weight: 32
---

# FastLink
C'est au cours de ma deuxième année d'études chez l'ESIEA que
j'ai effectué le projet FastLink. Il s'agissait d'un grand projet d'équipe 
fait sur un semestre avec quatre autres étudiants.
Pour moi, ce projet a représenté une véritable opportunité
d'apprendre en créant une application web complète, allant au delà
de la théorie vue en cours.

## Maîtriser les Outils et Collaborer de manière productive
Nous voulions développer un réseau social inspiré par Twitter. Au delà de la
simple reproduction de fonctionnalités, nous visions la mise en
place d'un système d'authentification fiable et
d'une architecture logicielle soignée et moderne.
Cela marquait une volonté de progrèssion par rapport à mes projets
precedents.
Mon rôle s'est concentré sur plusieurs fonctionnalités, principalement côté backend. Ce projet constituait
une exellente opportunité pour moi de :

- Monter significativement en compétence sur l'écosystème Spring Boot.
- Appliquer les bonnes pratiques de développement, notamment en explorant l'architecture en microservices.
- Renforcer mes acquis en modélisation de données relationnelles.
- Concevoir et mettre en œuvre une gestion des droits utilisateurs et des accès.

Ces objectifs correspondaient avec mon souhait d'approfondir mes
compétences techniques en développement backend. Le cadre temporel
du semestre nous a également conduits à adopter une gestion de
projet structurée et rigoureuse.

## Les Étapes Clés du Développement de FastLink
### Architecture et Technologies de FastLink
FastLink a été conçu comme une application web avec une
distinction claire entre le frontend et le backend. Pour la partie
backend, notre équipe a collectivement opté pour Java, en
s'appuyant sur le framework Spring Boot. La persistance des
données a été gérée via JPA/Hibernate et une base de donne PostgreSQL, et les
tests unitaires ont été réalisés avec JUnit.
L'utilisation de cette stack technologique, tres
exigeante pour un étudiant de 2ème année, s'est révélée être
une tres bonne expérience surtout en vue du fait que je l'utilise aujourd'hui en entreprise.
L'architecture globale du projet reposait sur le pattern MVC vue en semestre 1,
et nous avions opté pour une architecture en microservices
pour différentes fonctionnalités (gestion des utilisateurs, des
publications, etc.). Cette approche, bien que prometteuse sur le
papier, a présenté son propre lot de défis techniques.

### Le Système de Chat en Temps Réel
Parmi les différentes fonctionnalités sur lesquelles j'ai
travaillé, le développement du système de chat en temps
réel a représenté ma contribution la plus significative
et la plus complexe. Ce module a nécessité un travail approfondi
tant sur les aspects frontend que backend.
L'enjeu technique principal était dans la capacité à assurer
une communication instantanée et fluide entre les utilisateurs. Pour
y parvenir, j'ai implémenté un système basé sur lesWebSockets. 
Côté backend, cela a impliqué la
gestion des connexions WebSocket, le routage et la diffusion des
messages aux destinataires appropriés, ainsi que la persistance des
historiques de conversation. Côté frontend, j'ai travaillé sur
l'intégration de l'interface utilisateur du chat, afin de permettre
l'envoi et la réception des messages de manière intuitive et
réactive.
La mise en place de cette fonctionnalité a exigé un
apprentissage rapide des spécificités des WebSockets et de leur
intégration dans un environnement Spring Boot, tout en assurant une
coordination avec l'équipe pour l'interface utilisateur.

### Défis Techniques et Collaboratifs Rencontrés
Au delà du module de chat, le principal défi technique collectif
a été la mise en oeuvre d'une architecture microservices qui
soit réellement fonctionnelle. Assurer une communication
inter services fiable et performante en environnement de
développement local a nécessité plusieurs ajustements, notamment
pour la synchronisation des échanges.
La gestion de l'authentification et des autorisations
utilisateurs a également constitué une étape complexe, mais
essentielle du projet. Nous sommes parvenus à un système d'accès
sécurisé dont toute l'équipe était fière.
Sur le plan collaboratif, une communication claire et continue a
été importante pour se mettre d'accord sur la définition des API entre le
frontend et le backend. J'ai aussi pris en charge la
modélisation d'une partie de la base de données relationnelle, en
portant une attention particulière à sa cohérence.

## Bilan et Ce que nous avons Appris
Bien que FastLink soit un projet développé dans un cadre
académique, il a reçu un accueil très positif de la part
de nos professeurs. La robustesse de l'architecture
envisagée, la richesse fonctionnelle pour un projet de ce niveau,
notamment avec l'intégration du chat en temps réel, et la solidité
du système d'authentification ont été soulignés
et appréciés.
Pour l'ensemble de l'équipe, et pour moi personnellement, voir
l'application prendre vie et fonctionner correctement surtout les échanges instantanés via le chat a été unesource de grande satisfaction et de fierté. Ce
projet m'a permis d'atteindre les objectifs d'apprentissage que je
m'étais fixés concernant Spring Boot, les microservices, la
modélisation de données et, de façon très spécifique,
l'utilisation des WebSockets pour la communication
en temps réel.

## Perspectives et Leçons Apprises pour l'Avenir
Dans la période qui a suivi la réalisation de FastLink, les
compétences techniques et méthodologiques acquises, notamment en
développement backend avec Spring Boot et sur les technologies temps
réel comme les WebSockets, m'ont apporté une plus grande confiance pour
aborder des projets de plus grande complexité.
Ce projet a renforcé mon intérêt pour le
développement backend. Les défis techniques rencontrés et surmontés se
sont avérés extrêmement formateurs pour mieux appréhender la
complexité de different projets, surtout lors de mon alternance.

## Fierté et Axes de Progression
### Apports Majeurs du Projet à Mon Parcours
Avec le recul nécessaire, je considère FastLink
comme une étape véritablement déterminante de ma 2ème année
d'études. Ma contribution au développement backend, et 
surtout la conception et l'implémentation de bout
en bout du système de chat en temps réel, a été une
expérience exceptionnellement enrichissante.
Au delà des aspects purement technologiques, j'ai énormément
appris sur l'importance capitale de la rigueur dans la phase
de conception, de l'efficacité de la communication
au sein d'une équipe de développement, et de la recherche
constante de qualité dans le code produit.

### Ce que je Ferais Autrement Aujourd'hui
Cette expérience, tout en étant très positive, m'a également
permis d'identifier des axes d'amélioration pour mes futurs projets
:

- Une planification initiale des tâches et des dépendances encore plus détaillés permettrait d'anticiper certains blocages.
- L'instauration de revues de code systématiques.
- Une réflexion peut être plus poussée sur le découpage et l'architecture.

Néanmoins, ces réflexions critiques sont elles mêmes le fruit
de l'expérience précieuse acquise grâce à FastLink. Ce projet
a pu m'enseignant autant par ses succès que par
les défis qu'il a fallu relever. Il m'a fourni des bases techniques et
méthodologiques robustes pour la suite de mon parcours.
