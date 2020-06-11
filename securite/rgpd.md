# RGPD

_A chaque étape du développement d'un produit, savoir quelles questions se poser, quelles actions entreprendre, et quelles ressources mobiliser._

### Hygiène / grands principes

* Accepter que ces sujets coûtent du temps et des ressources et qu'ils ne sont pas \(très\) visibles des utilisateurs ; 
* Plus tôt on se pose les questions, plus il est facile et rapide d'y répondre et de traiter le sujet des données et de la sécurité ; 
* La relation de confiance qu'une équipe établit avec les référents-experts de ces sujets dans l'administration est son meilleur passeport pour la liberté et l'autonomie, davantage que les livrables attendus ;
* En matière de données, ce qui vaut pour soi vaut pour les autres : que n'aimerions-nous pas voir circuler sur nous-mêmes ? 

### Phase d'investigation

_9 semaines pour instruire un problème et envisager des solutions pour le résoudre_

#### Question\(s\) à se poser

* Quels outils utilisent l'équipe pour communiquer, prendre des notes, conduire des entretiens ?
* "Qui ça regarde ?" Est-ce que je suis en train de partager des données au delà du périmètre de l'équipe ou de ceux qu'elles regardent ? Un entretien utilisateur peut être partagé avec l'équipe, le coach, l'environnement de l'équipe, mais sans doute pas au-delà. Est-ce que j'ai autorisé la lecture de mon Google doc par défaut, ou l'ai-je restreint au cercle d'intéressés ?
* Est-ce que je sais ce qu'est une donnée personnelle ?

#### A faire :smile:

1. Je me documente sur les sujets RGPD & sécurité :
   * :bulb: [Qu'est-ce qu'une donnée personnelle ?](https://www.cnil.fr/fr/cnil-direct/question/une-donnee-caractere-personnel-cest-quoi) [Qu'est-ce qu'une donnée personnelle sensible ?](https://www.cnil.fr/fr/definition/donnee-sensible)
   * :bulb: [Guide d'hygiène informatique pour les systèmes d'information](https://www.ssi.gouv.fr/guide/guide-dhygiene-informatique/) & [Guide RGPD du dev](https://www.cnil.fr/fr/guide-rgpd-du-developpeur)
2. Je rencontre l'équipe juridique de la DINUM pour une première prise de contact :
   * Contacts : `perica.sucevic@modernisation.gouv.fr` , `ines.bedar@modernisation.gouv.fr`

     `cindy.kus@modernisation.gouv.fr` 
3. Je limite l'accès aux docs partagés à ceux que "ça regarde" et utiliser des outils différenciés en fonction du degré de gêne \(sensibilité\) des informations :
   * :bulb: pad.incubateur.net permet de prendre des notes. L'option "signed-in people can edit" limite la diffusion à la communauté @beta.gouv.fr.
4. Je minimise les informations collectées et supprime celles dont je n'ai pas besoin. Après un entretien utilisateur, ai-je besoin de conserver dans mes notes toutes les données de le personne interrogée \(date de naissance, numéro de tél, nom, etc.\) ?

_Un plan de déploiement peut être sur Google doc en accès ouvert, mais des notes d'entretien utilisateurs, plutôt en accès limité._

1. Je crée une fiche pour la nouvelle startup sur beta.gouv.fr 

#### A ne pas faire :frowning:

* Accepter de fichiers de coordonnées de personnes à contacter sans avoir vérifié le consentement de ces personnes ; 
* Discuter ou échanger des données personnelles sur des outils partagés \(Trello, Slack\). 

### Phase de construction

_3 mois pour développer une première solution numérique et trouver des utilisateurs_

#### Questions à se poser

* Quelle\(s\) donnée\(s\) personnelle\(s\) ai-je prévu de collecter ou d'utiliser dans mon produit, dans quel but précis ? 

Exemple : J'utilise des "traceurs" ou un outil de web analyse ; et je le fais dans le but d'optimiser le parcours sur le site.

* Suis-je en train de collecter des données dont je ne sais vraiment à quoi elles serviront ?
* Est-ce que le produit que je contruit peut se rattacher à une démarche administrative existante, un service, ou un texte juridique ? 
* Qui est mon référent RGPD \(DPO ou délégué DPO\) ou sécurité ?
* Quelle solution d'hébergement utilisai-je pour mon site ? Est-elle opérée ou localisée en France, Europe  ?   

#### A faire :smile:

1. Je rédige les Conditions Générales d'Utilisation \(CGU\) et Mentions Légales et les soumet à l'équipe juridique :
   * :bulb: Modèle à adapter : [Mes-aides](https://mes-aides.gouv.fr/cgu)
2. Je choisis les bons outils :
   * :bulb: Info et recommandation pour la gestion des cookies : [lien](https://beta.gouv.fr/suivi/)
3. Je recense toutes les données traitées et les finalités qui leur sont associées \[1 à 2h\] :
   * :bulb: [Tableau données-finalités](https://docs.google.com/document/d/1PQniGdnvLdjyEBbk1lFGzmG6rwnwD5bPCbvP_XBOe4I/edit?usp=sharing) écrit par la startup Itou. Le vôtre sera plus simple ! 
4. Si mon produit rentre dans l'un des [critères de la CNIL](https://www.cnil.fr/sites/default/files/atoms/files/liste-traitements-aipd-non-requise.pdf) : rédiger une analyse d'impact relative à la protection des donnée \(AIPD, aussi appelée EIVP\) :
   * :bulb: [Une AIPD, c'est quoi ?](https://www.cnil.fr/sites/default/files/atoms/files/infographie_aipd.pdf)
     * :bulb: [Exemple d'AIPD](https://docs.google.com/document/d/1j_1EESLdOHIa6bsYo3VSp-AJhPNPbQJKNRJnpJpRhKU/edit) pour la startup Itou 
5. Organiser un atelier d'analyse de risque en suivant le guide Agile de l'ANSSI \[1 demi-journée en équipe complète\] :
   * Exemple de [résultat d'un atelier](https://github.com/openmaraude/le.taxi/wiki/Analyse-des-risques) pour Le.taxi 
   * [Guide de sécurité Agile le l'ANSSI](https://www.ssi.gouv.fr/uploads/2018/11/guide-securite-numerique-agile-anssi-pa-v1.pdf)

_Pour la rédaction d'une AIPD, comme pour l'atelier d'analyse de risques, nous vous conseillons de solliciter l'aide d'un expert auprès de votre contact DINUM._ 

#### A ne pas faire :frowning:

* Fausse bonne idée : considérer que le recueil du consentement est nécessaire ou suffisant ou facile à mettre en oeuvre. Le consentement est en réalité souvent inutile dans l'administration, et complexe à stocker, gérer dans le temps.

### Phase d'accélération / Changement d'échelle

_Mon produit a rencontré ses utilisateurs et démontré sa valeur ; je concentre mes efforts sur son déploiements à grande échelle \(de 100 à 1000 ou de 1000 à 100 000 utilisateurs\)_

#### Question\(s\) à se poser

* Qui est le Responsable de la sécurité des systèmes d'information \(RSSI\) dans mon administration ? 

#### A faire :smile:

1. Je reviens sur les actions des phases précédentes, en répéter certaines \(atelier risques\) et mettre à jour les documents ; 
2. A partir du livrable de l'atelier risques, je constitue un dossier d'homologation de sécurité :
   * :bulb: Exemples de dossier d'homologation de sécurité : [Le.taxi](https://github.com/betagouv/beta.ssi/blob/master/homologations/le_taxi.md) et [Aidants connect](https://trello.com/c/NOap62w5) 
3. Je partage le dossier avec le RSSI de mon administration qui partage ses retours et me renseigne sur l'autorité d'homologation :
   * :bulb: Le RSSI de la DINUM est `laurent.voillot@modernisation.gouv.fr` 
4. \[Optionnel\] A ce stade, je peux solliciter un prestatire pour réaliser un test d'intrusion. Je contacte la DINUM si besoin pour en discuter. 

#### A ne pas faire :frowning:

* Déstaffer les développeurs expérimentés dont on a plus que jamais besoin pour la montée en charge du produit ; 
* Croire que c'est fini !  

