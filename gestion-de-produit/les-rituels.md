---
description: >-
  Les rituels et cycles de développement. Pourquoi et comment organiser un
  planning, une démo, une rétro, un daily standup ?
---

# Les rituels

_Documentation support pour rédiger la présentation de l’_[_Atelier Produit \#1_](https://docs.google.com/presentation/d/1OENBUfYHqi-Lsss0U0k2nYfT4q5sbkAVztTg7ZnKwLU/edit)\_\_

## **La théorie**

### L’origine de ce type de méthode 

Avant de parler des rituels et organisation des cycles de développement chez Beta.gouv, revenons quelques instant sur la genèse de ce type d’organisation.

#### **La méthode Scrum**

Scrum est un schéma d’organisation de développement de produits complexes, elle a pour objectif de livrer le plus efficacement des produits de la plus grande valeur possible. 

Elle est adapté aux équipe de développement et s'appuie sur le découpage d'un projet en boîtes de temps, nommées « sprints » qui durent en moyenne 2 semaines. Ce qui peut être fait pendant ces sprints se base sur des estimations de temps pour chaque tâche et de la vélocité de l’équipe \(nombre de ticket x nombre de “point de difficulté” appliqué à chacun\). 

Entre les sprints des moments de prise de recul permettent de mieux estimer ce qui pourra être fait au sprint suivant. 

#### **Les rituels**  

* Réunion de planification d'un sprint afin de décider des éléments du "backlog" qu'elle traitera dans le cadre de la prochaine itération, et comment elle s'organisera pour y parvenir
* Les Daily pour coordonner les développeurs sur les tâches en cours et sur les difficultés rencontrées
* La démo pour présenter et valider l'incrément de produit qui a été réalisé pendant le sprint
* La rétrospective qui a pour buts l'adaptation aux changements qui surviennent au cours du projet et l'amélioration continue du processus de réalisation

#### **Les protagonistes**

* le Product Owner est le représentant des clients et des utilisateurs. Il est « responsable de maximiser la valeur du produit et du travail de l'équipe de développement »
* le Scrum Master est responsable de la compréhension, de l'adhésion et de la mise en œuvre du framework
* l'équipe de développement est constituée de 3 à 9 personnes et a pour responsabilité de livrer à chaque fin d'itération une nouvelle version de l'application enrichie de nouvelles fonctionnalités et respectant le niveau de qualité nécessaire pour être livrée.

Cette méthode, appliquée à la lettre, se retrouve plutôt dans les SSII sur un format : client et cahier des charges d’un côté ; équipe de développement de l’autre. Elle est assez stricte et rigide dans son fonctionnement.

### **Les adaptations dans notre contexte** 

Dans le contexte d’équipe pluridisciplinaires et autonomes, comme à Beta.gouv mais aussi dans bon nombre de startups privées, on observe une adaptation de cette méthode plutôt qu’une application stricte. Les raisons sont nombreuses :

* elle a tendance à déresponsabiliser / “micro-manager” les équipes de développement 
* la charge d’organisation et de suivi est importante pour que celle-ci soit efficace 
* elle s’applique à des projets assez conçus de manière assez précise en amont et stables dans le temps
* elle intègre difficilement d’autres corps de métier dans son cycle 

Néanmoins, les grands principes sont gardés et les équipes s'adaptent en fonction de leur besoins. Le but reste le même : comment apporter un maximum de valeur durant les x prochaines semaines. Cette méthode donne un cadre et demande de passer de l’implicite \(auto organisation de chaque membre de l’équipe\) à l’explicite \(définition en amont des objectifs, rédaction de tâches à réaliser...\).   


Voici quelques conseils sur la mise en place de cette organisation :

#### **Pas de scrum master**

Le rôle du scrum master est important quand la méthode est appliquée à la lettre et que le respect du cadre implique beaucoup de travail \(organisation des réunions, des méthodes de travail, etc.\). Dans les équipes produit de beta gouv, comme dans les équipes produit classiques dans le privé, nous privilégions une organisation plus collaborative de ces réunions avec des responsabilités partagées entre les différents membres de l’équipe.

#### **Combien de temps pour un sprint ?**

Généralement entre 1 semaine et 1 mois.

Le plus commun étant 2 semaines, cela permet d’avoir un temps assez long de travail entre chaque période de “réunions” mais de pouvoir redresser le cap des priorités assez régulièrement. 

Si vous êtes dans une période très tendue pendant laquelle vous avez des incertitudes et des priorités changeantes, vous pouvez opter pour des sprints d’une semaine.

Si au contraire toute l’équipe est très au clair sur les priorités et ce qu’il y a à faire, vous pouvez allonger les sprints à 3 voire 4 semaines. 

#### **Qui participe ?**

Dans les startup privées on a l’habitude d’avoir une équipe produit formé de plusieurs développeurs, un designer, un product manager / product owner + d’autres profils selon l’équipe \(marketing, data, recherche utilisateur…\). Les rituels de sprint se font à minima avec cette équipe au complet.

Dans le cas des Startups d'État, et en fonction du nombre de personnes qui la composent, tous peuvent prendre part au sprint : intrapreneurs, chargés de déploiement, développeurs, coachs et autres profils. Si l’équipe est plus conséquente, faire participer le coeur de l’équipe de développement à tous les rituels et les autres uniquement sur certains d’entre eux.

#### **Les rituels**

**Le planning** 

Objectifs : fixer les objectifs et déterminer une stratégie pour l’atteindre. Pas besoin d’estimer chacune des tâches et d’avoir tous les tickets attribués pendant cette réunion mais de savoir où on veut aller.

Durée : de 30 minutes à 1 heure environ 

Participants : toutes les personnes qui participent au sprint, qui vont s’attribuer des tâches. Au minimum les développeurs et la personne jouant le rôle de chef de produit \(intrapreneur, product owner, business developer, etc.\)

Les points clés : se concentrer sur quelques objectifs principaux pour ne pas s’éparpiller - 1 à 3 maximum. Les tâches que chacun réalisera seront dans leur grande majorités attachées à répondre à ces objectifs

Déroulé : une ou plusieurs personnes sont en charge de la préparation de cette réunion : ils préparent un premier jet pour le sprint \(objectifs et quelques taches\) qui sera discuté et amélioré durant la réunion. Une personne anime la réunion de planning et prend en compte les retours de chacun.  


**Le daily** 

Objectifs : adapter le sprint en fonction des aléas

Durée : moins de 15 minutes

Participants : toutes les personnes qui participent au sprint

Les points clés : ce point est intéressant à faire en synchrone \(visio ou en physique\), surtout pour les équipes qui ont peu l’habitude de travailler ensemble ou si il y a un besoin de synchronisation important. Dans ce cas, il faut fixer un horaire et s’y tenir - au début de la journée de travail étant le mieux. Cela apporte de la stabilité pour l’équipe.   
Il peut être fait en asynchrone par Slack par exemple dans le cas d’équipes plus expérimentées ou de visibilité très importante sur les tâches et les objectifs.  
Garder la réunion très brève, si des questions sont soulevées, programmer un point dans la journée avec les personnes pertinentes. 

Déroulé : chacun annonce :

* ce sur quoi il a travaillé hier
* ce qu’il prévoit pour aujourd’hui
* les difficultés, le besoin d’aide 



**La rétrospective**

Objectifs : prendre du recul sur ce qu’il c’est passé durant le sprint, améliorer les process de travail. Parler des sujets autre que le travail également pour garder une équipe soudée.

Durée : de 30 minutes à 1 heure environ

Participants : toutes les personnes qui participent au sprint

Les points clés : cette réunion doit représenter un espace bienveillant, toutes les choses peuvent êtres dites pourvu qu’elles soient constructives. Il ne doit pas y avoir de tabous. C’est le moment ou chacun peut parler d’un sujet personnel qui l’affecte par exemple. Ce moment soude l’équipe.

Déroulé : Il existe différents format pour l’animer. Globalement il s’agit d’avoir des moments de réflexion seuls et des moments de restitution et d’échange en équipe. On doit faire ressortir ce qui s’est bien passé, pas bien passé, les pistes d’améliorations pour la suite.   


**La démo**

Objectifs : se rendre compte du travail effectué par l’équipe, “célébrer”.  Expliquer le fonctionnement des nouvelles fonctionnalités

Durée : de 30 minutes à 1 heure environ, selon le nombre de personnes présentes et la fréquence choisie

Participants : toutes les personnes qui participent au sprint, les personnes qui gravitent de près ou de loin autour du projet. Cela peut être une réunion “publique” car elle présente uniquement ce qui a été réalisé

Les points clés : cette réunion est un outil puissant de communication, souvent utile quand le produit est déjà assez mature, qu’il y a un nombre conséquent d’utilisateurs et que beaucoup de personnes s’y intéressent.  La présentation doit être claire, expliquer comment le produit fonctionne et les choix qui ont été faits. Idéalement, chaque personne présente le travail qu’il·elle a réalisé : les développeurs font une démo du produit, le·a designer présente un prototype ou des retours de test utilisateur, le·a chef·fe de produit présente une analyse de l’utilisation du site...

Déroulé : selon l’objectif et le nombre de personnes présentes le format ne sera pas le même. La réunion doit être préparée en amont, différentes personnes peuvent prendre la parole pour expliquer leur travail : développer, chargés de déploiement, designers… Il y a toujours un moment de démonstration du produit en live.   


#### **Comment gérer l’imprévu ?**

Bien sur, le planning ne permet pas de tout anticiper et il faut rester adaptable. Hormis un changement drastique de priorités qui remet le sprint en cause, 2 type de choses peuvent arriver : des bugs et des retours utilisateurs. 

Pour chacun, une compréhension et une évaluation de la priorité doit être faite et discutée en équipe - lors du daily ou sur le moment. Les sujets urgents vont rentrer dans le sprint et les autres seront mis dans le backlog ou dans un prochain sprint. Le but étant de garder une majorité de sujets prévus et une minorité d’imprévus - et pas l’inverse !  
****

#### **Les outils** 

Voici une grille d’évaluations de 4 types d’outils différents. Il en existe énormément, a vous de choisir selon vos critères. \(Pour info, plus de 90%  partie des startups  utilisent Trello ou Github \)  
****

<table>
  <thead>
    <tr>
      <th style="text-align:left"></th>
      <th style="text-align:left"><b>Trello</b>
      </th>
      <th style="text-align:left"><b>Github</b>
      </th>
      <th style="text-align:left"><b>Asana</b>
      </th>
      <th style="text-align:left"><b>JIRA</b>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Fonctionnement</b>
      </td>
      <td style="text-align:left">Vue &#x201C;board&#x201D; / &#x201C;Kanban&#x201D;. Les tableaux sont
        assez ind&#xE9;pendants entre eux</td>
      <td style="text-align:left">Liste de t&#xE2;ches. Possibilit&#xE9; de regrouper en milestones. &#xC9;galement
        une vue projet en Kanban</td>
      <td style="text-align:left">Espace de travail regroupant plusieurs projets. Liste ou Kanban pour des
        projets. Possibilit&#xE9; de liens entre projets</td>
      <td style="text-align:left">Vue board / kanban au choix, int&#xE9;gration des notions agile (sprints,
        user stories, epic, beaucoup de personnalisation</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Prix</b>
      </td>
      <td style="text-align:left">Gratuit</td>
      <td style="text-align:left">Gratuit</td>
      <td style="text-align:left">Gratuit jusqu&apos;&#xE0; 15 personnes avec des fonctionnalit&#xE9;s de
        base</td>
      <td style="text-align:left">- Gratuit jusqu&#x2019;&#xE0; 10 utilisateurs
        <br />- $7 / utilisateur / mois jusqu&#x2019;&#xE0; 100 utilisateurs</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Facilit&#xE9; d&#x2019;utilisation</b>
      </td>
      <td style="text-align:left">Fonctionnalit&#xE9;s simples, facile &#xE0; prendre en main.</td>
      <td style="text-align:left">Pas toujours facile &#xE0; prendre en main pour une personne lambda</td>
      <td
      style="text-align:left">Plus complexe que Trello mais une bonne exp&#xE9;rience utilisateur</td>
        <td
        style="text-align:left">Configuration de base rapide, mais peut vite devenir tr&#xE8;s complexe
          si l&#x2019;on souhaite personnaliser son fonctionnement</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Utilisateurs type</b>
      </td>
      <td style="text-align:left">Tout le monde</td>
      <td style="text-align:left">Plut&#xF4;t centr&#xE9; d&#xE9;veloppeur &#xE0; la base</td>
      <td style="text-align:left">Tout le monde</td>
      <td style="text-align:left">Chef de produit et d&#xE9;veloppeurs</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Avantages</b>
      </td>
      <td style="text-align:left">Adaptable &#xE0; tous les projets</td>
      <td style="text-align:left">1 outil pour la gestion de produit et la gestion de la base de code</td>
      <td
      style="text-align:left">Les diff&#xE9;rents projets permettant une gestion efficace de l&#x2019;&#xE9;quipe
        en 1 outil</td>
        <td style="text-align:left">Le plus complet du march&#xE9;. Int&#xE9;gration des notions agiles permet
          de s&#x2019;auto-former. Int&#xE9;gration dans l&#x2019;&#xE9;cosyst&#xE8;me
          Atlassian</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Inconv&#xE9;nients</b>
      </td>
      <td style="text-align:left">Peut vite devenir un peu fouilli quand on est beaucoup</td>
      <td style="text-align:left">Il faut de la rigueur pour garder le backlog propre. Pas adapt&#xE9; &#xE0;
        un sprint d&#x2019;une &#xE9;quipe tr&#xE8;s mixte dans les comp&#xE9;tences</td>
      <td
      style="text-align:left">Pas directement li&#xE9; &#xE0; Github pour les t&#xE2;ches techniques.
        Besoin de rigueur et de bien conna&#xEE;tre le produit pour en r&#xE9;cup&#xE9;rer
        la valeur</td>
        <td style="text-align:left">
          <p>Peut devenir complexe car beaucoup de choses sont personnalisables</p>
          <p>A souvent une image de &#x201C;grosse machine&#x201D;</p>
        </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Recommandations</b>
      </td>
      <td style="text-align:left">Tr&#xE8;s bien au d&#xE9;but quand on est peu &#xE0; travailler sur le
        projet</td>
      <td style="text-align:left">Si l&#x2019;&#xE9;quipe est tr&#xE8;s tech, ce produit convient bien -
        quelque soit la taille de l&#x2019;&#xE9;quipe</td>
      <td style="text-align:left">Pour une &#xE9;quipe pluridisciplinaire que se structure, elle permet
        d&#x2019;&#xEA;tre l&#x2019;unique outil de gestion de projet</td>
      <td style="text-align:left">Tr&#xE8;s bon outil si une personne connait son fonctionnement et est
        capable d&#x2019;onboarder le reste de l&#x2019;&#xE9;quipe
        <br />Plutot pour des &#xE9;quipes importantes et produits complexes</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Exemple d&#x2019;&#xE9;quipe l&#x2019;utilisant</b>
      </td>
      <td style="text-align:left">E-controle</td>
      <td style="text-align:left">Code Du Travail Num&#xE9;rique</td>
      <td style="text-align:left">Peps</td>
      <td style="text-align:left">Pas Culture</td>
    </tr>
  </tbody>
</table>

#### **Le long terme**

Les objectifs de chaque sprint s’inscrivent dans un contexte plus global de priorités fixées sur plusieurs mois. Ces priorités sont formalisées dans un document ou une roadmap, elles sont partagées avec des différentes parties prenante sur le sujet. Il est important de fixer ces priorités et d’y travailler pendant plusieurs sprint afin d’avoir un réel impact sur les objectifs visés comme la rétention d’un type d’utilisateur, l’acquisition de nouveaux prospects, la qualité de service… 

L’important est d’essayer un format et de le faire évoluer en équipe. Les rétros sont alors précieuse pour cette évolution.  
****

#### **Autres modèles de fonctionnement**

Le scrum n’est pas l’unique base pour organiser le développement de son produit. Une autre méthode est souvent citée, le Kanban. Elle consiste en une liste priorisée et réduite de tâches à faire qui s'actualise au fur et à mesure des développements. Il reste important d’y attacher des rituels de priorisation, de suivi et de rétrospective car c’est ceux-ci qui permettent l’efficacité de l’équipe. Ces rituels sont à définir par l'équipe.  
****

#### **Besoin d’aide ?**

Si vous avez besoin d’aide pour créer, adapter, animer ou améliorer vos rituels, vous pouvez demander à la communauté sur \#domaine-produit

#### **Articles et pistes de réflexion**

* [**https://blog.thiga.co/product-owner-donnez-du-peps-a-vos-retrospectives/**](https://blog.thiga.co/product-owner-donnez-du-peps-a-vos-retrospectives/)
* [**https://www.intercom.com/blog/continue-stop-start-retrospectives/**](https://www.intercom.com/blog/continue-stop-start-retrospectives/)
* [**https://www.intercom.com/blog/product-seminars-that-dont-suck/**](https://www.intercom.com/blog/product-seminars-that-dont-suck/)
* [**https://www.intercom.com/blog/continuous-flow-weekly-planning/**](https://www.intercom.com/blog/continuous-flow-weekly-planning/)

## **Retour d’expérience**

**Lery et Estelle avec e-contrôle :** [**Rituels de Sprint - e.contrôle**](https://docs.google.com/document/d/1I2uFdTEZSmyFEAVS5doQwYuceCf4wZzeqMQYIxXTSxo/edit#heading=h.23p755cgeckc)  


