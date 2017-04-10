---
layout: post
title: "Manipulation de Java Bytecode avec Javassist"
speaker: "Jerome Kehrli"
slides: ""
date: 2017-04-27 18:30:00
---
Le Bytecode Java est le nom donné à la forme binaire des instructions exécutées par la JVM. Normalement, un programmeur Java se soucie assez peu de la façon dont fonctionne le bytecode Java.

Une certaine compréhension du bytecode, et plus important encore une façon de le manipuler, sont cependant essentiels aux domaines de l'outillage et de l'analyse de programme, où les applications peuvent modifier le bytecode pour ajuster le comportement selon le domaine de l'application. Les profilers, les outils de "mocking", les frameworks AOP, ORM, les conteneurs IoC, les générateurs de "boilerplate" code, etc. nécessitent de bien comprendre le bytecode Java et des moyens de le manipuler au "runtime". Chacune de ces fonctionnalités avancées qui sont aujourd'hui des approches de programmation de l'ordre du standard nécessitent une bonne compréhension du bytecode Java, sans mentionne des languages complètement nouveaux fonctionnant sur JVM telles que Scala ou Clojure.

Manipuler le bytecode repose traditionnellement sur des librairies et techniques complexes. Javassist, cependant, propose une approche naturelle, simple et efficace qui apporte les possibilités de manipulation du bytecode à tout un chacun.

Cette session JUGL vise à présenter Javassist à la lumière de deux use cases: les conteneurs IoC et la génération de code "boilerplate".

#### Speaker

Jérôme Kehrli est titulaire d'un diplôme d'ingénieur en informatique logicielle de la HEIG-VD et d'un MSc en Engineering de la HES-SO, il a 15 années d'expérience en conception, développement et réalisation d'applications ainsi qu'en gestion de projet.

Ses différentes expériences ont amené Jérôme à se spécialiser dans l'architecture générale des systèmes d'informations, en étant très orienté sur les problématiques de calculs ou les traitements en temps-réel dans le monde des banques et des assurances.

En plus de son expérience importante dans le développement de logiciel bancaire, Jérôme apporte sa curiosité et sa passion des technologies innovantes pour inspirer et diriger la R&D de [NetGuardians](http://www.netguardians.ch/) qu'il a rejoint en 2015.
