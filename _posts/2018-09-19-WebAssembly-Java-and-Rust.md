---
layout: post
title: "Faciliter le développement d'applications Web rapides avec WebAssembly"
speaker: "Benjamin Bouvier"
slides: "https://youtu.be/YrUj1UeVOkA"
date: 2018-09-19 18:30:00
---

WebAssembly se propose comme un nouveau standard du Web, disponible dans tous les navigateurs modernes, destiné à la compilation vers le Web. Les promesses sont d'envergure : faire abstraction du langage source en proposant un format de bytecode, et obtenir des performances proches du natif grâce à une plateforme d'exécution sécurisée, directement intégrée dans le navigateur.

Pourquoi s'intéresser à WebAssembly aujourd'hui ? Est-ce que c'est simple à utiliser ? Comment peut-on en tirer profit facilement dès maintenant ? Nous essayerons ensemble de répondre à ces questions, puis nous verrons comment créer et intégrer du code WebAssembly, en passant par toutes les étapes, de l'écriture du code source initial en Rust jusqu'à l'intégration dans une application Web.

Nous verrons ensuite quel est l'état de l'art de la compilation vers
WebAssembly pour les langages de la JVM, ainsi que les fonctionnalités
nécessaires pour pouvoir l'exécuter efficacement.

#### Speaker

Benjamin Bouvier est ingénieur en compilation chez Mozilla dans l'équipe WebVM. Cette équipe s'occupe de la machine virtuelle Spidermonkey embarquée dans le moteur de rendu de Firefox (Gecko), qui exécute le JavaScript et le WebAssembly des applications web. Avant ça, il a travaillé sur asm.js, un sous-ensemble facilement optimisable de JavaScript aux performances élevées, proches du natif. Il s'est également impliqué dans le développement de SIMD.js, une API expérimentale de calcul parallèle. Désormais il travaille sur la standardisation et l'implémentation de WebAssembly dans Firefox.
