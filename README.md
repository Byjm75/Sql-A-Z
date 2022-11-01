                            BASE DE DONNEES DE A-Z

Une BASE DE DONNEES ou BDD est un outil informatique qui permet d’organiser des informations de façon sécurisée, hiérarchisée et sans doublon.
Appelée Database en anglais (on voit souvent l’abbréviation db), les bases de données sont des logiciels qui permettent surtout de mieux travailler.

BASE DE DONNEES RELATIONNELLE
Relationnelle se dit d’une base de données qui manipule des informations hiérarchisées qui sont liées entre elle par des contraintes de relations.
À la différence d’autres types de bases de données, les bases de données relationnelles fonctionnent avec des tableaux à deux dimensions nommés tables qui sont liés à d’autres tables par un mécanisme de relations reposant sur l’algèbre relationnelle.
Ces relations définissent et précisent les liens entre les tables.

MERISE est une méthode informatique dédiée à la modélisation qui analyse la structure à informatiser en terme de systèmes. Le gros avantage de cette méthode est qu’elle permet de cadrer le projet informatique et de « discuter » en se comprenant entre utilisateurs et informaticiens.
Merise est en fait un outil analytique qui facilite la création de base de données et de projets informatique.
Concrètement Merise permet de :
-Hiérarchiser les préoccupations du gestionnaire de projet informatique
-Décrire le fonctionnement du système à informatiser et notamment :
Les données (MCD) : quelles sont les relations et les dépendances entres les différents acteurs
(client – commande – produit – fournisseur par exemple)
Les traitements (MCT) : comment les acteurs travaillent-ils ensemble
(comment se passe une commande concrètement par exemple)
Proposer une implémentation logique (MLD, MLT) du point précédent
Proposer une construction concrète et utilisable du point précédent (MPD, MOT)

APPLICATION DANS LES BASES DE DONNEES
CRUD => Create, Read, Update, Delete. (Écrire, Lire, Mettre à jour, Supprimer).
Il s’agit des opérations de base attendues par un SGBD (mais pas uniquement, on s’en sert aussi dans d’autres types de logiciels).
L'acronyme CRUD se réfère à la majorité des opérations implémentées dans les bases de données relationnelles. Chaque composante de l'acronyme peut être associée à un type de requête en SQL ainsi qu'à une méthode HTTP1,2.

Operation SQL HTTP = requete Postman
Create INSERT PUT (en) / POST (en)
Read (Retrieve) SELECT GET (en)
Update (Modify) UPDATE PUT (en) / PATCH (en)
Delete (Destroy DELETE DELETE (en)

LA MODELISATION
En conception de base de données, la modélisation est l’étape indispensable qui permet de comprendre les processus métiers et de les transcrire informatiquement en flux de données et de traitements.
La modélisation est la brique indispensable qui permet de construire une base de données solide et conforme aux attentes des utilisateurs.
Cette étape est préalable à la construction concrète de la base de données et la construction des différents écrans que manipuleront les utilisateurs.
|
|
UML Abréviation de United Modeling Langage.(Langage de Modélisation unifié)
UML est un outil souvent utilisé en développement informatique.
Il permet via des outils graphiques de représenter le fonctionnement d’un outil informatique (c’est particulièrement vrai en Programmation Orientée Objet ou UML permet de modéliser directement les objets qui seront ensuite manipulés par le programme informatique).
Outil plus récent que Merise, UML propose une petite quinzaine de diagrammes qui ne remplacent pas Merise.
Les 2 outils ont des objectifs différents :
Merise est un ensemble cohérent pour construire des bases de données.
C’est une méthode idéale de modélisation pour construire une base de données relationnelle.
UML ne propose pas de démarche ni d’organisation (ce n’est pas une méthode).
C’est un outil idéal pour la conception logiciel dans un langage de type objet.
Les 2 peuvent fonctionner indépendamment ou de concert.
|
| -Utilisation de UML avec l'outil Diagammes.net-
|
MCD (Modèle Conceptuel des Données)
Est un des outils majeurs concernant les données.
Le MCD est une représentation graphique de haut niveau qui permet facilement et simplement de comprendre comment les différents éléments sont liés entre eux.
Faisant partie de la boîte à outil Merise, le MCD décrit les données utilisées par le système d’information et leurs relations.
Les informations sont représentées logiquement en utilisant un ensemble de règles et de diagrammes codifiés :
-Les entités (1 rectangle = 1 objet);
-Les propriétés (la liste des données de l’entité);
-Les relations qui expliquent et précisent comment les entités sont reliées entre elles
(les ovales avec leurs « pattes » qui se rattachent aux entités);
-Les cardinalités (les petits chiffres au dessus des « pattes »).
Utilisé assez tôt en conception de base de données, le MCD sert de base de travail et sera ensuite utilisé par les autres outils de Merise, à savoir le MPD et le MLD.
Le MCD constitue une étape très importante de la modélisation.
Si cette tâche est mal réalisée, des erreurs en cascade se produiront et rejailliront sur le MPD, le MLD et sur la base de données finale.
On peut ainsi à partir d’un MCD valider et préciser des règles qui s’appliqueront à la future base de données.
|
|
MLDR Modèle Logique des Données Relationnel
Est la représentation textuelle du MPD.
Il s’agit juste de la représentation en ligne du schéma représentant la structure de la base de données.
Il n’y a pas de travail poussé à réaliser à cette étape, il s’agit juste d’appliquer quelques règles toutes simples.
On représente ainsi les données issues de la modélisation Merise sous la forme suivante :
-Chaque ligne représente une table ;
-C’est toujours le nom de la table qui est écrit en premier ;
-Les champs sont listés entre parenthèses et séparés par des virgules ;
-Les clés primaires sont soulignées et placées au début de la liste des champs ;
-Les clés étrangères sont préfixées par un dièse.
|
|
SQL (sigle de Structured Query Language, en français langage de requête structurée)
Le SQL est le langage informatique qui permet de définir et de manipuler les bases de données.
En SQL, on peut par exemple interroger une base de données, ajouter, modifier et supprimer des données.
Il est aussi possible de réaliser des opérations lourdes (gestion de tables) ou de maintenance / performance (gestion des index…).
LES REQUETES
Une requête est une opération effectuée sur une base de données. Réalisée en langage SQL, elle permet :
-Rechercher une information au sein d’une base de données en imposant des conditions et en effectuant des filtres et des tris. Le résultat est alors présenté de façon tabulaire.
-Agir sur la structure de la base de données en y ajoutant / modifiant / supprimant des éléments et en y réalisant des opérations de maintenance.
-Agir sur les données (ajout / modification / suppression).
SGBD Systéme de Gestion de Base de Données (DataBase Management System)
Il s’agit du logiciel qui permet de créer une base de données.
Non utilisable directement par l’utilisateur final, le SGBD est un logicile intermédiaire employé par le concepteur pour se soulager de toutes les tâches indispensables inhérentes au fonctionnent de sa base de données.
PostgreSQL est un outil de système de gestion de base de données relationnelle et objet.
Concurrent: MySQL, Oracle, Microsoft SQL Server...
--Outil DBeaver--
--Outil PostgreSQL--

MCT (Modèle Conceptuel des Traitements)
Dans la méthodologie Merise, il y a tout un pan de l’analyse qui porte sur les traitements.
Le MCT en fait partie.
Il présente graphiquement, sous la forme de schémas avec des éléments bien définis, les traitements qui doivent être informatisés.
Il permet d’identifier le fonctionnement du système d’information.
Dit autrement, il répond au QUOI.
Le MCT est le miroir du MCD.
Le MCD se focalise sur les données alors que le MCT se focalise sur les réponses à donner lorsqu’un événement survient.
Les 2 sont complémentaires et agissent au niveau conceptuel, c’est à dire qu’il cherchent à modéliser le fonctionnement d’un point de vue métier.
Le MCT détaille les processus en événements et en opérations :
-Un événement est un déclencheur ou un résultat. Il peut être externe ou interne (dans le Système d’Information);
-La synchronisation est l’ensemble des conditions à remplir pour déclencher une opération en fonction des événements entrants. On utilise ici la logique booléenne ;
-Une opération est effectuée suite au déclenchement d’un ou plusieurs événements. C’est la somme des actions à réaliser d’un coup. On utilise un verbe pour l’exprimer ;
-Des règles d’émission sont définis dans l’opération
-Un processus est une suite chaînée d’événements et d’opérations. Dans sa version la plus simple, un MCT à un événement en entrée, une opération et un événement en sortie.

MLT

Outil pour SGBDR Diagrammes.net
MPD (Modèle Physique des Données)
Dans la méthodologie Merise, le MPD fait suite au MCD.
L’étape de création du MPD est presque une formalité comparée à la création du MCD.
En s’appuyant sur des règles simples, l’analyste fait évoluer sa modélisation de haut niveau pour la transformer en un schéma plus proche des contraintes des logiciels de bases de données.
Il s’agit de préparer l’implémentation dans un SGBDR.
Concrètement, cette étape permet de construire la structure finale de la base de données avec les différents liens entre les éléments qui la composent.
Pour la peine, on change aussi de vocabulaire :
Les entités se transforment en tables ;
Les propriétés se transforment en champs (ou attributs) ;
Les propriétés se trouvant au milieu d’une relation génèrent une nouvelle table ou glissent vers la table adéquate en fonction des cardinalités de la relation ;
Les identifiants se transforment en clés et se retrouvent soulignés.
Chaque table dispose d’au minimum 1 clé dite primaire ;
Les relations et les cardinalités se transforment en champs parfois soulignés : il s’agit de créer des « clés étrangères » reliées à une « clé primaire » dans une autre table.

Requete URL-SQL avec Postman

------------------------SOUTIEN----------------------------------
shéma fonctionnement API Node.js (slide)

Route: fetch(localhost:8080/api/listHero).
Notre site => requete url => route (fonction du verbe HTTP) => Réponse à notre site.
API = chercher la definission
