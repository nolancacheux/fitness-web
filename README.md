# Fitness-Web

Bienvenue sur le dépôt du projet Fitness-Web, un site de musculation développé en PHP, CSS, MySQL et PHPMyAdmin en binôme. Il s'agit d'une plateforme complète comprenant une boutique, des comptes clients, des fonctionnalités de connexion et d'inscription, des menus, une section contact, un panier, la gestion des cookies, des objectifs et des produits.

## Table des matières

- [Prérequis](#prérequis)
- [Installation](#installation)
- [Configuration](#configuration)
- [Utilisation](#utilisation)
- [Contribuer](#contribuer)
- [Licence](#licence)

## Prérequis

Pour utiliser ce projet, vous devez avoir les logiciels suivants installés sur votre machine :

- PHP 7.4 ou supérieur
- MySQL 5.7 ou supérieur
- Un serveur web (Apache, Nginx, etc.)
- PHPMyAdmin (recommandé pour gérer la base de données)

## Installation

1. Clonez ce dépôt sur votre machine locale :
- `git clone https://github.com/nolancacheux/fitness-web.git`

2. Importez la base de données dans MySQL en utilisant PHPMyAdmin ou la commande suivante :
- `mysql -u root -p site < fitness-web/inc/site.sql`

3. Configurez votre serveur web pour qu'il pointe vers le dossier `fitness-web`.

## Configuration

1. Accédez au fichier `fitness-web/inc/init.inc.php` et modifiez les informations de connexion à la base de données si nécessaire :
```
$ $hostname= 'localhost'; //nom du serveur (localhost)`
$ $username='root';//nom d'utilisateur pour accéder au serveur (root)`
$ $password='root'; //mot de passe pour accéder au serveur (root)`
$ $dbname='site'; //nom de la base de données`
```

Vérifiez que la constante RACINE_SITE est correctement définie pour correspondre au chemin de votre projet sur votre serveur web :

-`define("RACINE_SITE","/site/");`

## Utilisation
Une fois l'installation et la configuration terminées, vous pouvez accéder à votre site Fitness-Web depuis votre navigateur en entrant l'adresse correspondante.

## Contribuer
Les contributions sont les bienvenues ! N'hésitez pas à ouvrir des issues ou des pull requests pour proposer des améliorations ou des corrections.

## Licence
Ce projet est sous licence MIT. Veuillez consulter le fichier LICENSE pour plus d'informations.


