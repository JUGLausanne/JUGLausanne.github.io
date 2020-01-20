---
layout: post
title: "PRetours de la KotlinConf 2019 et utilisation FullStack de Kotlin"
speaker: "Gaetan Zoritchak"
slides: ""
date: 2020-01-22 18:30:00
---

1. KotlinConf 2019
Revenant de la KotlinConf 2019, Gaetan débutera la soirée par un retour sur les principales annonces de la conférence ainsi que les présentations les plus marquantes.

2. Kotlin Fullstack
Dès le départ, Kotlin a été conçu pour être déployable dans divers contextes et plateformes: back et front, JVM, JS et natif.
Dans un de nos derniers projets web, nous avons profité de cette caractéristique pour utiliser Kotlin au maximum, dans toutes les couches de notre application.
Nous détaillerons l'architecture de ce projet lors de cette présentation, et comment nous avons utilisé des librairies multiplateformes pour partager du code entre le serveur et le navigateur.
Les librairies et projets utilisés sont:
- xodus-dnq, pour définir le modèle de données et accéder à la base xodus,
- Ktor comme framework web,
- Kotlinx.hmtl pour le templating html, serveur et client,
- Kotlinx.serialization pour le partage d’état entre le serveur et le client,
- Kotlin/JS et une implémentation interne de Redux pour le code client.

#### Speaker

Gaetan Zoritchak, ayant assimilé beaucoup de langages informatiques pendant les 20 années d'expériences qu'il a eu dans le domaine de l'informatique, a très rapidement été convaincu par les promesses de Kotlin. Gaetan utilise Kotlin depuis plusieurs années. Il se l'est approprié en 2012 et à commence à le promouvoir dès 2013 en tant qu'orateur.

Après l'avoir déployé en production sur du backend, il a démarré un nouveau projet en 2017 nommé "data2viz.io". Le but de ce dernier est de créer une librairie multiplateforme de data-visualisation en Kotlin.