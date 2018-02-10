# Exercices d'entretien pour développeur

Voici quelques exercices d'entretien que j'ai réalisé afin d'évaluer les compétences de développeurs. Vous trouverez des exercices à destination de développeurs Front et Back-End ainsi que des exercices de conception visant à évaluer la création et la réflexion d'un candidat autour d'une problématique.

## Exercices
### 1 - Utilisation d'une API Rest (Front)

#### Enoncé
En utilisant l'API Rest de [The Movie DB](https://developers.themoviedb.org/3), vous allez devoir créer une application qui permet d'aller rechercher un film en fonction de son titre et d'en lire les informations essentielles. 

#### Outils disponibles

Vous devrez développer en **Javascript (ES6) ou en Typescript**. Vous êtes complêtement libre visuellement d'utiliser ce que vous souhaitez (Bootstrap, Foundation ou autre). Vous pouvez utiliser les framework suivant si vous le souhaitez : *VueJS*, *React*, *Angular*, *Backbone.js**. 

#### Livrable

Vous devrez fournir l'ensemble du code source.
L'application sera testée sur un navigateur Chrome récent. Vous pouvez également fournir une application Electron si vous le souhaitez.

### 2 - Utilisation d'une API Rest (Back PHP)

#### Enoncé

En utilisant l'API Rest de [The Movie DB](https://developers.themoviedb.org/3), vous allez devoir créer une application qui permet d'aller rechercher un film en fonction de son titre et d'en lire les informations essentielles. 

#### Outils disponibles

Vous devrez fournir l'ensemble du code source.
Vous devrez développer en **PHP 7+**, ne pas utiliser de base de données. Vous pouvez utiliser les frameworks suivants : *Laravel*, *Symfony*. Il est recommandé d'utiliser une bibliothèque comme *Guzzle*.

#### Livrable

L'application sera testée sur une instance *Heroku*, si nécessaire veuillez fournir la documentation afin de mettre en place celle-ci. 

### 3 - Conception d'un système de réplication de fichiers.

#### Enoncé

Vous avez des serveurs en France et en Allemagne qui partagent le même système de fichiers. Aujourd'hui, dans votre code toutes les écritures de fichiers sont doublées et toutes les lectures sont tentées uniquement sur les serveurs locaux. Cela pose deux problèmes :
1. Vous devez à chaque écriture de fichier penser à la faire aux deux endroits.
2. Parfois un fichier n'est pas présents en local mais disponible sur le dépot distant. Ce n'est pas normal, mais vous aimeriez que l'on utilise le fichier distant de manière transparente.

Ecrivez une classe PHP 7+ qui servira d'interface unique pour gérer l'écriture et la lecture de ces fichiers. Cela pourra ressembler à une façade comme celle-ci :

```php
class Media {
    static public function getFile($filename) {
        // ...
    }
    static public function setFile($filename, $content) {
        // ...
    }
}
```

Vous pouvez cependant définir autant de classes que nécessaire pour répondre proprement au problème.

Vous savez par ailleurs qu'il est prévu d'ouvrir des serveurs en Italie bientôt. Et vous pensez également qu'il faudra s'occuper des problèmes de fichiers manquants sur certains serveurs.

Vous symboliserez chaque serveur par un dossier différent (`/france` et `/allemagne`).

#### Outils disponibles

Aucun framework et aucune bibliothèque tierce n'est autorisé.

#### Livrable

Vous devrez fournir l'ensemble du code source.