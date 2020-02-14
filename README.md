## RentCar Questions

### Qu'est-ce qu'un container de services ? Quel est son rôle ?
Un container de service est juste un objet qui gères l'instanciaton des services.

Son rôle est de pouvoir justement gagner du temps et ne pas récréer manuellement l'objet à chaque fois qu'on en as besoin 

### Quelle est la différence entre les commandes make:entity et make:user lorsqu'on utilise la console Symfony ?

La commande `make:entity` permet de générer une classe lié à un objet et avec les champs nécessaire
Alors que la commande `make:user`permet de générer une classe lié à un user en ajoutant des fonctionnalités particulères.

### Résumez de manière simple le fonctionnement du système de versions "Semver"

Semver permet de numéro les versions du projet en fonction de l'avancement, de façon claire et intuitive.

### Quelle commande utiliser pour voir la liste des routes ?

`php bin/console debug:router`

### Dans un template Twig, quelle variable globale permet d'accéder à la requête courante, l'utilisateur courant, etc...?

Il s'agit de la variable `app`

### Pour mettre à jour la structure de la base de données, quelles sont les 2 possibilités que nous avons abordées en cours ?

Dans un premier temps nous avons vu les migrations et dans un second les ...

### Quelle commande utiliser pour charger les fixtures dans la base de données ?

`php bin/console doctrine:fixtures:load`

### Quelle commande permet de créer une classe de contrôleur ?
`php bin/console make:controller`

### Décrivez succintement l'outil Flex de Symfony
L'outil Flex est un plugin Composer qui gère l'installation et la gestion des applications Symfony

### Qu'est-ce qu'un Repository ? A quoi sert-il ?
Repository est une méthode de conception permettant de faciliter les tests et de bénéficier d'une structure optimale
