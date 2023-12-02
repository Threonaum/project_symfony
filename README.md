# project_symfony

## Avant de débuter le projet

j'ai pris le temps de lire plusieurs fois l'énoncé que ce soit pour le côté théorique mais aussi pour le côté pratique. Après lecture, j'ai d'abord été rassuré car l'entièreté a été vu en cours. Cependant, j'appréhende toujours autant car j'ai peur de ne pas y arriver. 
C'est pourquoi j'ai pris l'initiative de commencer par répondre aux questions avant de commencer mon projet. Malgré tout, j'ai déjà crée le "squelette" de mon projet. 

## Sommaire 

### Le projet en lui-même

* Rappel de l'énoncé [s'y rendre](#rappel-de-lénoncé)
* Problèmatiques rencontrées [s'y rendre](#problèmatiques-rencontrées)
* Fonctionnalités présentes dans le projet [s'y rendre](#fonctionnalités-présentes-dans-le-projet)
* Ressources utilisées [s'y rendre](#ressources-utilisées)
* Conclusion [s'y rendre](#conclusion)

### Les réponses aux questions

1. Qu'une qu'un container de services et quel est son rôle ? <span style="background-color: yellow;">Texte avec fond jaune</span>

    -un container de services c'est l'ensemble des classes compilées de notre application. Son rôle est de contenir des informations ( dont les services ) afin de pouvoir les utiliser quand on en a besoin à l'endroit où l'on en a besoin. 

2. Quelle est la diffèrence entre les commandes ```make:entity``` et ```make:user``` lorsqu'on utilise la console Symfony ? 

    -la commande ```make:entity``` permet de créer des entités via le "maker" et de les configurer en fonction de son type, son "état" (nullable, unique), etc. C'est ce qui donnera des "tables" dans notre base de données.

    -la commande ```make:user``` permet de créer des utilisateurs via le "maker" et de nous permettre de les intégrer comme nous le souhaitons dans notre application.

    Par conséquent, la diffèrence entre ces deux commandes est que la première permet de créer nos entités qui donneront les attributs de nos tables dans la base de données tandis que la deuxième nous permet de créer nos entités utilisateurs ainsi que leurs paramètres.

3. Quelle commande utiliser pour charger les fixtures dans la base de données ? 

    -la commande qu'il faut utiliser pour charger les fixtures dans la base de données est ```php bin/console doctrine:fixtures:load``` que l'on peut écrire aussi ```php bin/console d:f:l```.

4. Résumez de manière simple le fonctionnement du système de versions "Semver".

    -Le système de versions "Semver" est le système qu'a choisi d'utiliser Symfony pour son versionning. 
    Il fonctionne de la manière suivante :

    Tous les deux ans, une nouvelle version majeure est créée, durant ces deux ans, plusieurs versions mineures sont créées tous les 6 mois. De cette manière l'on peut ainsi voir la version de symfony de cette façon :

    "version majeure"."version mineure", par exemple la version sur laquelle je fais mon projet est la 6.4 soit, la 6e version majeure ainsi que la 4e et dernière version mineure de la 6e version majeure. 

    Les dernières versions mineures sont appelées des "LTS" pour "Long Term Support", car ces versions mineures ont 3 ans de support, correction de bug, sécurité, etc ... assurés. 

5. Qu'une ce qu'un "repository" et à quoi sert-il ? 
6. Quelle commande utiliser pour voir la liste des routes ?
7. Dans un template twig, quelle variable globale permet d'accéder à la requète courante, l'utilisateur courant, etc ?
8. Pour mettre à jour la structure de la base de données, quelles sont les deux possibilités que nous avons abordées en cours ?
9. Quelle commande permet de créer une classe de contrôleur ?
10. Décrivez succintement l'outil flex de symfony.

#### Rappel de l'énoncé 
[haut de page](#sommaire)


#### Problèmatiques rencontrées
[haut de page](#sommaire)


#### Fonctionnalités présentes dans le projet
[haut de page](#sommaire)


#### Ressources utilisées
[haut de page](#sommaire)


#### Conclusion
[haut de page](#sommaire)