# Le Kit de démarrage de la startup d'état

Votre objectif pour les 6 premiers mois est d'avoir impacté au moins un usager, et cela avec un code répondant aux standard de betagouv en terme de front (accessibilté), back (Sécurité) et données utilisateurs (RGPD)

Pour cela, nous mettons à la disposition des SE un ensemble d'outil nommé le starter kit.
- Gestionnaire de version : [Le compte github de betagouv](https://github.com/betagouv)
- Un design system : qui vous donne des éléments ré-utilisable et dont l'accessibilté a déjà été travaillée 
> le [design system](https://gouvfr.atlassian.net/wiki/spaces/DB/pages/223019574/D+veloppeurs) est visible sur [template.incubateur.net](https://template.incubateur.net)
- Un hébergement : nous préconisons l'utilisation de [Scalingo](https://scalingo.com/fr) avec un hebergement secnumcloud
> Scalingo est un PaaS qui permet de pousser sur un serveur via git. Cela implique une infra as code.
- Un systeme d'analytics : [stats.data.gouv.fr](https://stats.data.gouv.fr)
> Matomo est hebergé par nos soins. Ce service est respectueux des données utilisateur, et le configurer comme préconisé par la CNIL permet de suivre son audience sans avoir à mettre un bandeau avertissant les visiteur sur le dépos de cookies.
> Attention ! Le nombre de visiteur sur votre site est rarement l'équivalent d'une mesure d'impact. 
- Trois langages de référence : Ruby (RoR), javascript (Express) et python (Django). Ces langages ont été selectionné pour leur flexibilité, et les options "out of the box" en terme de sécurité des SI et la facilité de prise en main en cas de passage à l'échelle.
> Si vous utilisez Express, vous pouvez directement cloner le repo [du template](https://github.com/betagouv/template-design-system-de-l-etat) pour avoir rapidement une V0 de votre site.

## Standard de qualité produit

- l'équipe est pilotée par un processus de design proche des usagers : Il est normal pour les dévellopeur•euses d'aller à la rencontre des usagers, et d'inveter des usager aux séances de design.
> L'équipe Aidants Connect se demande comment organiser la liste des usagers sur son service. Ils invitent Sandrine à leur atelier pour voir avec elle la façon dont elle utilise cette liste aujourd'hui et les filtres et option de tri dont elle a besoin.
- l'équipe est à l'écoute des usagers et accessible:
    - pas d'adresses mail "no reply"
    - répond à chaque contact usager
    - adopte une posture "basse" et servicielle
- les sites sont sécurisés par SSL
> Cette option est disponible en un clic sur Scalingo. 
- une page /stats rend compte des mesures d'impact
- le langage est clair, direct et sans jargon

## Standards de qualité logicielle

- le code source est ouvert, y compris à la contribution externe
- le code est instrumenté par des tests automatisés
- le code est déployé fréquemment, idéalement en continu
- Le code est écrit en utilisant les standards du langages (ex : pep8 en python) ou du framework
