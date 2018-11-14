# Questionnaire Dev Ops

Document réalisé par *Vincent Demonchy* pour la société *Kizeo*.

## PHP

### 1 - Expliquez la différence entre les opérateurs suivants :

- `&`
- `&&`
- `AND`

### 2 - Quel est le résultat de ce code :

```php
$a = 'ki' || 'wi';
$b = 'ki' or 'wi';
var_dump($a, $b);
```

### 3 Que fait ce code ?

```php
$a = $monArray['elementA'] ?? 'Ah...';
$b = $monArray['elementB'] ?: 'Oh...';

var_dump($a, $b);
```

### 4 - Vous avez 50 tables dans votre base de données qui ont un mécanisme de soft-delete commun, 20 autres n'en ont pas, toutes héritent d'une même classe représentant un modèle d'objet en base de données appelée `Model`. Comment géreriez-vous cela ?

### 5 - Et sachant que 25 d'entre-elles, réparties équitablement dans les deux groupes, ont les colonnes `created_at` et `updated_at` représentant des timestamp?

<div style="page-break-after: always;"></div>

## Choix technologiques

### 1 - Expliquez-moi les avantages et les inconvénients entre PHP et NodeJS

### 2 - Expliquez-moi les avantages et les inconvénients entre PostgreSQL et MongoDB

### 3 - Comment stockeriez-vous les informations sur un utilisateur d'une plateforme E-commerce dans chacun" de ces bases ?

<div style="page-break-after: always;"></div>

## Docker

### 1 - Décrivez-moi un Dockerfile commençant par la ligne ci-dessous permettant d'avoir un serveur Apache fonctionnel en HTTP (pour distribuer des fichiers, sans PHP ni rien)

```dockerfile
FROM ubuntu:18.04
# ... A compléter
```

### 2 - Décrivez-moi le fichier `docker-composer.yml` représentant une stack PHP (web) plutôt complète.

<div style="page-break-after: always;"></div>

## Administration système

Je me trouve dans un dossier contenant des centaines de fichiers nommés ainsi `YYYY-MM-DD_hh:ii.log`. Je suis sur une machine Debian 9.

### 1 - Comment renvoyer l'ensemble des fichiers effectués le 9 Novembre 2017 ?

### 2 - Comment trouver les fichiers contenant à l'intérieur le texte `211.113.64.32` ?

Pour les questions suivantes, je suis sur une machine Linux quelconque (par exemple Debian).

### 3 - Comment vérifier l'espace restant sur les partitions ?

### 4 - Comment créer un fichier vide ?

### 5 - Comment poser une clé SSH sur un autre serveur ?