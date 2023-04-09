# Fitness-Web

Bienvenue sur le d�p�t du projet Fitness-Web, un site de musculation d�velopp� en PHP, CSS, MySQL et PHPMyAdmin en bin�me. Il s'agit d'une plateforme compl�te comprenant une boutique, des comptes clients, des fonctionnalit�s de connexion et d'inscription, des menus, une section contact, un panier, la gestion des cookies, des objectifs et des produits.

## Table des mati�res

- [Pr�requis](#pr�requis)
- [Installation](#installation)
- [Configuration](#configuration)
- [Utilisation](#utilisation)
- [Contribuer](#contribuer)
- [Licence](#licence)

## Pr�requis

Pour utiliser ce projet, vous devez avoir les logiciels suivants install�s sur votre machine :

- PHP 7.4 ou sup�rieur
- MySQL 5.7 ou sup�rieur
- Un serveur web (Apache, Nginx, etc.)
- PHPMyAdmin (recommand� pour g�rer la base de donn�es)

## Installation

1. Clonez ce d�p�t sur votre machine locale :
- `git clone https://github.com/nolancacheux/fitness-web.git`

2. Importez la base de donn�es dans MySQL en utilisant PHPMyAdmin ou la commande suivante :
- `mysql -u root -p site < fitness-web/inc/site.sql`

3. Configurez votre serveur web pour qu'il pointe vers le dossier `fitness-web`.

## Configuration

1. Acc�dez au fichier `fitness-web/inc/init.inc.php` et modifiez les informations de connexion � la base de donn�es si n�cessaire :
```
$ $hostname= 'localhost'; //nom du serveur (localhost)`
$ $username='root';//nom d'utilisateur pour acc�der au serveur (root)`
$ $password='root'; //mot de passe pour acc�der au serveur (root)`
$ $dbname='site'; //nom de la base de donn�es`
```

V�rifiez que la constante RACINE_SITE est correctement d�finie pour correspondre au chemin de votre projet sur votre serveur web :

-`define("RACINE_SITE","/site/");`

## Utilisation
Une fois l'installation et la configuration termin�es, vous pouvez acc�der � votre site Fitness-Web depuis votre navigateur en entrant l'adresse correspondante.

## Contribuer
Les contributions sont les bienvenues ! N'h�sitez pas � ouvrir des issues ou des pull requests pour proposer des am�liorations ou des corrections.

## Licence
Ce projet est sous licence MIT. Veuillez consulter le fichier LICENSE pour plus d'informations.


