---
description: >-
  Les rituels et cycles de développement. Pourquoi et comment organiser un
  planning, une démo, une rétro, un daily standup ?
---

# Les rituels

## Objectif & contexte

Cette documentation a pour but de présenter rapidement les différents rituels \(= réunions d'équipe régulières\) qu'une équipe produit peut mettre en place afin de travailler le plus efficacement et d'aider chacun à se sentir partie-prenante de la construction du produit.

Nous allons parler de différentes méthodes d'organisation mais ce document n'est pas une recommandation officielle pour inciter les équipes des Startups d'Etat à utiliser une méthode plutôt qu'une autre, plutôt une inspiration pour celles et ceux qui souhaiteraient mettre en place une équipe produit ou améliorer son organisation :\)

## Présentation

Cette documentation a été présentée pendant l'Atelier produit \#1 le 22 avril 2020 : [Les rituels et cycles de développement](https://docs.google.com/presentation/d/1OENBUfYHqi-Lsss0U0k2nYfT4q5sbkAVztTg7ZnKwLU/edit)

## Organisation de l'équipe

### Les méthodes agile et Scrum 

Les rituels que nous allons présenter sont majoritairement issus des méthodes agile en général et de la méthode Scrum en particulier. Avant de détailler le pourquoi et le comment de ces rituels et de l'organisation des cycles de développement, revenons quelques instant sur ces méthodes.

#### Scrum

Scrum est un schéma d’organisation de développement de produits complexes, elle a pour objectif de livrer le plus efficacement des produits de la plus grande valeur possible. Elle est adaptée aux équipe de développement et s'appuie sur le découpage d'un projet en boîtes de temps, nommées « sprints » qui durent en moyenne 2 semaines. Ce qui peut être fait pendant ces sprints se base sur des estimations de temps pour chaque tâche et de la vélocité de l’équipe \(nombre de ticket x nombre de “point de difficulté” appliqué à chacun\). Entre les sprints des moments de prise de recul permettent de mieux estimer ce qui pourra être fait au sprint suivant. 

Les protagonistes dans une équipe Scrum :

* le Product Owner est le représentant des clients et des utilisateurs. Il est « responsable de maximiser la valeur du produit et du travail de l'équipe de développement »
* le Scrum Master est responsable de la compréhension, de l'adhésion et de la mise en œuvre du framework
* l'équipe de développement est constituée de 3 à 9 personnes et a pour responsabilité de livrer à chaque fin d'itération une nouvelle version de l'application enrichie de nouvelles fonctionnalités et respectant le niveau de qualité nécessaire pour être livrée.

Pour plus d'informations, vous pouvez vous reporter à [l'article Wikipedia sur le sujet](https://fr.wikipedia.org/wiki/Scrum_%28d%C3%A9veloppement%29).

#### **Kanban**

Le scrum n’est pas l’unique base pour organiser le développement de son produit. Une autre méthode est souvent citée, le Kanban. Elle consiste en une liste priorisée et réduite de tâches à faire qui s'actualise au fur et à mesure des développements. Il reste important d’y attacher des rituels de priorisation, de suivi et de rétrospective car c’est ceux-ci qui permettent l’efficacité de l’équipe. Ces rituels sont à définir par l'équipe.

Pour plus d'informations, vous pouvez vous reporter à [l'article Wikipedia sur le sujet](https://fr.wikipedia.org/wiki/Kanban).

### **Les adaptations dans notre contexte** 

Dans le contexte d’équipe pluridisciplinaires et autonomes, comme à Beta.gouv mais également dans la majorité des équipes produit modernes, on observe une adaptation de ces méthodes plutôt qu’une application stricte afin de correspondre au mieux à l'équipe et à ses contraintes.

Néanmoins, les grands principes sont gardés et les équipes s'adaptent en fonction de leurs besoins. Le but reste le même : comment apporter un maximum de valeur durant les x prochaines semaines. Cette méthode donne un cadre et demande de passer de l’implicite \(auto organisation de chaque membre de l’équipe\) à l’explicite \(définition en amont des objectifs, rédaction de tâches à réaliser...\). 

Voici quelques conseils sur la mise en place de cette organisation :

#### **Pas de scrum master**

Le rôle du scrum master est important quand la méthode est appliquée à la lettre et que le respect du cadre implique beaucoup de travail \(organisation des réunions, des méthodes de travail, etc.\). Dans vos équipes produit, il est préférable de privilégier une organisation plus collaborative de ces réunions avec des responsabilités partagées entre les différents membres de l’équipe.

#### **Combien de temps pour un sprint ?**

Généralement entre 1 semaine et 1 mois.

Le plus commun étant 2 semaines, cela permet d’avoir un temps assez long de travail entre chaque période de “réunions” mais de pouvoir redresser le cap des priorités assez régulièrement. Si vous êtes dans une période très tendue pendant laquelle vous avez des incertitudes et des priorités changeantes, vous pouvez opter pour des sprints d’une semaine. Si au contraire toute l’équipe est très au clair sur les priorités et ce qu’il y a à faire, vous pouvez allonger les sprints à 3 voire 4 semaines.

Vous pouvez également ne pas faire de sprints \(par exemple en vous basant sur la méthode Kanban\) mais il reste important d'avoir des rituels d'équipe réguliers.

#### **Qui participe ?**

Une équipe produit est habituellement formée de plusieurs développeurs, un designer, un product manager / product owner + d’autres profils selon l’équipe \(marketing, data, recherche utilisateur…\). Les rituels de sprint se font à minima avec cette équipe au complet.

Dans le cas des Startups d'État, et en fonction du nombre de personnes qui la composent, tous peuvent prendre part au sprint : intrapreneurs, chargés de déploiement, développeurs, coachs et autres profils. Si l’équipe est plus conséquente, faire participer le coeur de l’équipe de développement à tous les rituels et les autres uniquement sur certains d’entre eux.

## **Les rituels**

### **Le planning** 

Objectifs : fixer les objectifs et déterminer une stratégie pour l’atteindre. Pas besoin d’estimer chacune des tâches et d’avoir tous les tickets attribués pendant cette réunion mais de savoir où on veut aller.

Durée : de 30 minutes à 1 heure environ 

Participants : toutes les personnes qui participent au sprint, qui vont s’attribuer des tâches. Au minimum les développeurs et la personne jouant le rôle de chef de produit \(intrapreneur, product owner, business developer, etc.\)

Les points clés :

* se concentrer sur quelques objectifs principaux pour ne pas s’éparpiller - 1 à 3 maximum
* les tâches que chacun réalisera seront dans leur grande majorités attachées à répondre à ces objectifs

Déroulé : une ou plusieurs personnes sont en charge de la préparation de cette réunion : ils préparent un premier jet pour le sprint \(objectifs et quelques taches\) qui sera discuté et amélioré durant la réunion. Une personne anime la réunion de planning et prend en compte les retours de chacun.

Bien sur, le planning ne permet pas de tout anticiper et il faut rester adaptable. Hormis un changement drastique de priorités qui remet le sprint en cause, 2 type de choses peuvent arriver : des bugs et des retours utilisateurs. 

Pour chacun, une compréhension et une évaluation de la priorité doit être faite et discutée en équipe - lors du daily ou sur le moment. Les sujets urgents vont rentrer dans le sprint et les autres seront mis dans le backlog ou dans un prochain sprint. Le but étant de garder une majorité de sujets prévus et une minorité d’imprévus - et pas l’inverse !

Les objectifs de chaque sprint s’inscrivent dans un contexte plus global de priorités fixées sur plusieurs mois. Ces priorités sont formalisées dans un document ou une roadmap, elles sont partagées avec des différentes parties prenante sur le sujet. Il est important de fixer ces priorités et d’y travailler pendant plusieurs sprint afin d’avoir un réel impact sur les objectifs visés comme la rétention d’un type d’utilisateur, l’acquisition de nouveaux prospects, la qualité de service… 

### **Le daily** 

Objectifs : adapter le sprint en fonction des aléas

Durée : moins de 15 minutes

Participants : toutes les personnes qui participent au sprint

Les points clés :

* ce point est intéressant à faire en synchrone \(visio ou en physique\), surtout pour les équipes qui ont peu l’habitude de travailler ensemble ou si il y a un besoin de synchronisation important. Dans ce cas, il faut fixer un horaire et s’y tenir - au début de la journée de travail étant le mieux. Cela apporte de la stabilité pour l’équipe
* il peut être fait en asynchrone par Slack par exemple dans le cas d’équipes plus expérimentées ou de visibilité très importante sur les tâches et les objectifs
* Garder la réunion très brève, si des questions sont soulevées, programmer un point dans la journée avec les personnes pertinentes

Déroulé : chacun annonce :

* ce sur quoi il a travaillé hier
* ce qu’il prévoit pour aujourd’hui
* les difficultés, le besoin d’aide 

### **La rétrospective**

Objectifs : prendre du recul sur ce qu’il c’est passé durant le sprint, améliorer les process de travail. Parler des sujets autre que le travail également pour garder une équipe soudée.

Durée : de 30 minutes à 1 heure environ

Participants : toutes les personnes qui participent au sprint

Les points clés : 

* cette réunion doit représenter un espace bienveillant, toutes les choses peuvent êtres dites pourvu qu’elles soient constructives. Il ne doit pas y avoir de tabous
* c’est le moment ou chacun peut parler d’un sujet personnel qui l’affecte par exemple, ce moment soude l’équipe

Déroulé : Il existe différents format pour l’animer. Globalement il s’agit d’avoir des moments de réflexion seuls et des moments de restitution et d’échange en équipe. On doit faire ressortir ce qui s’est bien passé, pas bien passé, les pistes d’améliorations pour la suite. 

### **La démo**

Objectifs : se rendre compte du travail effectué par l’équipe, “célébrer”.  Expliquer le fonctionnement des nouvelles fonctionnalités

Durée : de 30 minutes à 1 heure environ, selon le nombre de personnes présentes et la fréquence choisie

Participants : toutes les personnes qui participent au sprint, les personnes qui gravitent de près ou de loin autour du projet. Cela peut être une réunion “publique” car elle présente uniquement ce qui a été réalisé

Les points clés : 

* cette réunion est un outil puissant de communication, souvent utile quand le produit est déjà assez mature, qu’il y a un nombre conséquent d’utilisateurs et que beaucoup de personnes s’y intéressent
* la présentation doit être claire, expliquer comment le produit fonctionne et les choix qui ont été faits.
* idéalement, chaque personne présente le travail qu’il·elle a réalisé : les développeurs font une démo du produit, le·a designer présente un prototype ou des retours de test utilisateur, le·a chef·fe de produit présente une analyse de l’utilisation du site...

Déroulé : selon l’objectif et le nombre de personnes présentes le format ne sera pas le même. La réunion doit être préparée en amont, différentes personnes peuvent prendre la parole pour expliquer leur travail : développer, chargés de déploiement, designers… Il y a toujours un moment de démonstration du produit en live. 

## **Retour d’expérience**

Lery et Estelle présentent leur rituels \(planning et rétrospective\) sur e-contrôle : [Rituels de Sprint - e.contrôle](https://docs.google.com/document/d/1I2uFdTEZSmyFEAVS5doQwYuceCf4wZzeqMQYIxXTSxo/edit#heading=h.23p755cgeckc)

## **Articles et pistes de réflexion**

* [**https://blog.thiga.co/product-owner-donnez-du-peps-a-vos-retrospectives/**](https://blog.thiga.co/product-owner-donnez-du-peps-a-vos-retrospectives/)
* [**https://www.intercom.com/blog/continue-stop-start-retrospectives/**](https://www.intercom.com/blog/continue-stop-start-retrospectives/)
* [**https://www.intercom.com/blog/product-seminars-that-dont-suck/**](https://www.intercom.com/blog/product-seminars-that-dont-suck/)
* [**https://www.intercom.com/blog/continuous-flow-weekly-planning/**](https://www.intercom.com/blog/continuous-flow-weekly-planning/)

## **Besoin d’aide ?**

Si vous avez besoin d’aide pour créer, adapter, animer ou améliorer vos rituels, vous pouvez demander à la communauté sur \#domaine-produit.

## \*\*\*\*

