<!-- This file is the homepage of your Log4brains knowledge base. You are free to edit it as you want -->

# Base de connaissance

Bienvenue 👋 dans la base de connaissances sur l'architecture de solutions.
Vous trouverez ici tous les relevés de décisions d'architecture (ADR) du projet.

ce site est basé sur le code source [log4brains](https://github.com/thomvaill/log4brains/).

## Definition et Objectif

Une **décision d'architecture (DA)** est un choix de conception logicielle qui répond à une exigence fonctionnelle ou non fonctionnelle significative sur le plan de l'architecture.

Un **enregistrement de décision d'architecture (ADR)** capture une seule décision d'architecture, comme c'est souvent le cas lors de la rédaction de notes personnelles ou de comptes rendus de réunions ; l'ensemble des ADR créées et conservées dans le cadre d'un projet constitue son journal des décisions.

Un **ADR est immuable** : seul son statut peut changer (c'est-à-dire devenir obsolète ou remplacé). Ainsi, vous pouvez vous familiariser avec l'historique complet du projet en lisant simplement son journal de décisions dans l'ordre chronologique.

En outre, le maintien de cette documentation vise à :

- 🚀 Améliorer et accélérer l'intégration d'un nouveau membre de l'équipe
- 🔭 Éviter l'acceptation/le retour aveugle d'une décision passée (cf. le célèbre article de Michael Nygard sur les [ADR](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions.html))
- 🤝 Formaliser le processus de décision de l'équipe
  
## Utilisation

Ce site web est automatiquement mis à jour après un changement sur la branche `master` du dépôt Git du projet.

En effet, les développeurs gèrent cette documentation directement avec des fichiers markdown situés à côté de leur code, il est donc plus pratique pour eux de la maintenir à jour.

Vous pouvez parcourir les ADR utilisant le menu de gauche ou la barre de recherche.

Les étapes typiques d'un ADR est le suivant :

![Flux de travail ADR](/l4b-static/adr-workflow.png)

Le processus de décision est entièrement collaboratif et soutenu par des demandes d'extraction.

## Pour plus d'information

- [Log4brains documentation](https://github.com/thomvaill/log4brains/tree/master#readme)
- [What is an ADR and why should you use them](https://github.com/thomvaill/log4brains/tree/master#-what-is-an-adr-and-why-should-you-use-them)
- [ADR GitHub organization](https://adr.github.io/)
