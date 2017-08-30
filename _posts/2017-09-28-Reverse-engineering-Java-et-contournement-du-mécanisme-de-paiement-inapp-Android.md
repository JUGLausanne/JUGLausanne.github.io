---
layout: post
title: "Reverse engineering Java et contournement du mécanisme de paiement inapp Android"
speaker: "Jérémie Matos"
slides: ""
date: 2017-09-28 18:30:00
---
Android fournit une API Java pour la facturation d'achats in-app, permettant aux développeurs de vendre des fonctionnalités supplémentaires directement depuis l'application. Ce mécanisme est très souvent utilisé dans les jeux pour acheter des crédits donnant accès à du contenu supplémentaire, des bonus, etc ... Mais l'intégration du paiement est souvent mal comprise: on ne peut pas faire confiance au code tournant sur le smartphone. Ainsi, toutes les vérifications et l'obtention du contenu doivent s'effectuer côté serveur. Comme ce n'est pas très clair dans la documentation de Google, beaucoup de jeux continuent de faire la gestion côté client.

Nous allons exploiter une véritable application Android du Playstore pour obtenir des crédits gratuits. Et constater à quel point il est facile d'en faire son reverse engineering et d'identifier les validations effectuées côté client. Puis grâce au framework de hooking Xposed, nous allons écrire un hook tenant en une seule ligne de code Java permettant de contourner le paiement. Enfin, nous verrons comment patcher le bytecode de l'application (afin d'y injecter le hook) pour être ensuite capable de la distribuer très facilement.

Pour conclure, des recommandations pratiques seront données pour se prémunir de ce genre de problème en utilisant Angry Birds comme exemple.

####Speaker

Jeremy Matos (@SecuringApps) a travaillé dans le domaine de la sécurité logicielle depuis plus de 10 ans en Suisse Romande. Avec une formation académique de développeur, il a conçu et participé à l'implémentation d'une solution innovante d'authentification forte mobile.

Il a également effectué des revues de code et des audits sécurité pour des sociétés dont l'utilisateur interne était l'ennemi ou craignant pour leur réputation.

Il fournit désormais des services en sécurité applicative au sein de sa propre société. Il a présenté l'année dernière au Crypto Village de la DefCon un nouveau vecteur d'attaque contre les messageries mobiles chiffrées appelé Man In The Contacts.

Il enseigne également la sécurité logicielle et les technologies blockchain pour des formations d'ingénieur en Suisse et en France.
