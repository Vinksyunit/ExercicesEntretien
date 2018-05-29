# 3 - Conception d'un système de réplication de fichiers.

#### Temps estimé

Environ 2h30

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

Vous devrez fournir l'ensemble du code source sur GitHub. Dans cet exercice, la manière est plus importante que le résultat visuel, ainsi il n'est pas demandé de réaliser une quelconque interface.