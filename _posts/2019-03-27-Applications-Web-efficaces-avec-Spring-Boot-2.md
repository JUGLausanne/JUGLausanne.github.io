---
layout: post
title: "Applications Web efficaces avec Spring Boot 2"
speaker: "Stéphane Nicoll"
slides: ""
date: 2019-03-27 18:30:00
---

Comment peut-on améliorer l'efficacité et la scalabilité d'une application Web existante? On pourrait complètement la réécrire, avec programmation plus concurrente, fonctionnelle, ou réactive. Mais est-ce que ça vaut vraiment le coup, sans mesurer et savoir où concentrer nos efforts?

Dans cette présentation en live coding, Stéphane va travailler sur une application Spring Boot MVC existante. Pour la rendre pour efficace. Il va remplacer `RestTemplate` par `WebClient` et utiliser des opérateurs Reactor pour améliorer la scalabilité, sans tomber dans les pièges de la programmation concurrente.

Il va utiliser des métriques fournies par Spring Boot, en ajouter des personnalisées, et garder un oeil sur les gains de capacité dans des dashboards.

#### Speaker

Stéphane Nicoll a un faible pour la qualité de code des logiciels et leur robustesse. Il a répandu le mot pendant plus de 10 ans alors qu'il développait des applications Java d'entreprises, de grande échelle, dans les secteurs du géospatial, de la finance ou encore de la logistique. Membre PMC d'Apache Maven depuis 2006, il rejoint l'équipe de développement du framework Spring en 2014. Il est devenu depuis l'un des principaux contributeurs du framework ainsi que de Spring Boot. Pendant son temps libre, il aime voyager à travers le monde.