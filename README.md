# Projet O'INVEST

O'INVEST est un projet réalisé en août 2023 en collaboration avec le centre de formation O'Clock dans le cadre du diplôme de Développeur Web & Web Mobile. 
Ce projet a été développé sur une période d'un mois, avec pour objectif la création d'une application de gestion de portefeuille boursier en équipe, depuis la conception jusqu'à la réalisation d'un MVP fonctionnel.
Objectif

L'objectif principal était de concevoir une application permettant à l'utilisateur de gérer efficacement son portefeuille d'actions en intégrant des fonctionnalités de suivi des cours boursiers en temps réel. 
L'idée initiale était de trouver et d'utiliser une API permettant de récupérer les prix des actions à une date et une heure spécifiques, puis de les intégrer dans le portefeuille sélectionné.

Une fonctionnalité clé du projet était de permettre à l'utilisateur de comparer les cours des actions en portefeuille avec les cours actuels. 
Cela permet à l'utilisateur de visualiser les gains ou pertes latentes, tant au niveau du portefeuille que des actions individuelles.
Technologies Utilisées

Frontend: Réalisé en React, le frontend récupère les données transmises par le backend via des endpoints, offrant ainsi une interface utilisateur réactive et intuitive.
Backend: Le backend est développé en JavaScript avec un serveur Node.js, assurant ainsi une gestion efficace des requêtes et des données.

## Difficultés Rencontrées

Nous avons rencontré des défis dans la recherche d'API satisfaisantes dans leur version gratuite. Par conséquent, nous avons dû limiter notre MVP au marché du NASDAQ, avec une capacité maximale de 8 actions en portefeuille. Nous avons utilisé deux API principales pour cela :

    Une API pour les actions NASDAQ: 

Cette API nous a fourni une liste à jour des actions du NASDAQ, y compris les secteurs d'activité et leurs TICKER correspondants. 

Par exemple :
        Tesla, secteur Automobile (TSLA)
        Moderna, secteur Biotechnologie (MRNA)
        Et bien d'autres...

    Financial Modeling Prep API: 
Dans sa version gratuite à l'époque (août 2023), cette API nous a limités à 8 appels par minute et 800 par mois. Cependant, elle nous a permis d'accéder aux données financières des actifs en utilisant leur TICKER.

## Équipe

Notre équipe était composée de quatre membres, travaillant à 100 % en télétravail et communiquant via Slack et Discord :

    TENSORER Alexandre: Ancien gestionnaire de patrimoine et initiateur de l'idée du projet.
    ALIBAY Razack: Expert en analyse de données et développement back-end.
    BECKER Benjamin: Développeur front-end spécialisé en React.
    MAREL Jerome: Développeur front-end spécialisé en React.

## Conclusion

Le projet O'INVEST représente notre engagement en tant qu'équipe à fournir des solutions innovantes dans le domaine de la gestion de portefeuille boursier. 
Je suis particulièrement fier du MVP que nous avons développé malgré les défis rencontrés. 
Cette application, bien que conçue pour un projet d'école, témoigne de notre savoir-faire et de nos compétences en matière de développement web et mobile.

Notre objectif principal avec O'INVEST n'est pas nécessairement de continuer à développer l'application,
 mais plutôt de s'en servir comme un présentation du travail que nous avons su fournir. 

Nous sommes convaincus que les fonctionnalités que nous avons implémentées, malgré les limitations des API et les contraintes de temps, 
démontrent notre capacité à relever des défis et à fournir des solutions fonctionnelles et intuitives.
