# Le Kit de démarrage de la Startup d'État

Votre objectif pour les 6 premiers mois est d'avoir de l'impact sur au moins un usager, et cela avec un code répondant aux standards de beta.gouv/.Fr en terme de front (accessibilté), back (Sécurité) et données utilisateurs (RGPD)

Pour cela, nous mettons à la disposition des Startups d'État un ensemble d'outils nommé le "Kit de démarrage".
- Gestionnaire de versions : [Le compte github de beta.gouv.fr](https://github.com/betagouv)
- Un design system : qui vous donne des éléments ré-utilisables et dont l'accessibilité a déjà été travaillée 
> le [design system](https://gouvfr.atlassian.net/wiki/spaces/DB/pages/223019574/D+veloppeurs) est visible sur [template.incubateur.net](https://template.incubateur.net)
- Un hébergement : nous préconisons l'utilisation de [Scalingo](https://scalingo.com/fr) (entreprise référencée à l'UGAP et donc mobilisable dans le respect du code de la commande publique), avec un hebergement secnumcloud
> Scalingo est un PaaS qui permet de pousser sur un serveur via git. Cela implique une infra as code.
- Un systeme d'analytics : [stats.data.gouv.fr](https://stats.data.gouv.fr)
> Matomo est hébergé par nos soins. Ce service est respectueux des données des utilisateurs, et le configurer comme préconisé par la CNIL permet de suivre son audience sans avoir à mettre un bandeau avertissant les visiteurs sur le dépôt de cookies.
> Attention ! Le nombre de visiteurs sur votre site est rarement l'équivalent d'une mesure d'impact. 
- Trois langages de référence : Ruby (RoR), javascript (Express) et python (Django). Ces langages ont été selectionnés pour leur flexibilité, et les options "out of the box" en terme de sécurité des SI et la facilité de prise en main en cas de passage à l'échelle.
> Si vous utilisez Express, vous pouvez directement cloner le repo [du template](https://github.com/betagouv/template-design-system-de-l-etat) pour avoir rapidement une V0 de votre site.

## Contraintes légales

Dans le cadre du travail avec l'administration, il est important de connaitre les contraintes légales en terme de Sécurité, RGPD et Accessibilité.
- Si vous souhaitez les consulter vous pourrez les trouver sur la page dédiée au [RGPD et sécurité](https://doc.incubateur.net/startups/rgpd-and-securite/guide-rgpd-securite) et à l'[accessibilité](https://doc.incubateur.net/design/ressources-design/kit-accessibilite/obligations-legales)
- Nous proposons aussi une formation dédiée : contactez Anna-Livia pour plus d'informations

## Standard de qualité produit

- l'équipe est pilotée par un processus de design proche des usagers : Il est normal pour les dévelopeur•euses d'aller à la rencontre des usagers, et d'inviter des usagers aux séances de design.
> L'équipe Aidants Connect se demande comment organiser la liste des usagers sur son service. Ils invitent Sandrine à leur atelier pour voir avec elle la façon dont elle utilise cette liste aujourd'hui et les filtres et option de tri dont elle a besoin.
- l'équipe est à l'écoute des usagers et accessible:
    - pas d'adresses mail "no reply"
    - répond à chaque demande d'un usager
    - adopte une posture humble et servicielle
- les sites sont sécurisés par SSL
> Cette option est disponible en un clic sur Scalingo. 
- une page /stats rend compte des mesures d'impact
- le langage est clair, direct et sans jargon
- l'équipe développe le produit dans un esprit de sobriété, en priorisant les fonctionnalités les plus simple possible pour prouver l'impact sur les usagers (par exemple : prioriser une FAQ bien documentée à un chatbot)

## Standards de qualité logicielle

- le code source est ouvert, y compris à la contribution externe
- le code est instrumenté par des tests automatisés
- le code est déployé fréquemment, idéalement en continu
- le code est écrit en utilisant les standards du langages (ex : pep8 en python) et du framework
