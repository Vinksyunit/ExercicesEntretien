# 6 - Application Allo Vegan (site Web React/Vue)

#### Temps estimé

Entre 1 et 2 heures

#### Enoncé

Vous ferez **un site web moderne** dont l'objectif est de faire découvrir des restaurants vegans autour de chez vous. Ce site peut soit être réalisé avec *React* ou *Vue.js*. Aucun back-end n'est autorisé.

Pas besoin d'héberger un serveur, pour trouver la liste des restaurants, il suffit d'invoquer cette URL en remplaçant les valeurs de `VOTRELATITUDE` et `VOTRELONGITUDE` :

https://xlmd94l53b.execute-api.eu-west-2.amazonaws.com/api?lat=VOTRELATITUDE&long=VOTRELONGITUDE

Cette URL renverra les 10 restaurants les plus proches (les données sont générées aléatoirement ici, donc pas de persistance entre deux chargements). Attention, la documentation fournie par ce service n'est pas très fournie.

Le site devra demander à l'utilisateur de se géolocaliser (en lui demandant de renseigner son adresse) et lui permettre de voir sous forme de liste, à la façon *AlloResto*. 

#### Outils disponibles

Vous devrez développer en **Javascript (ES6) ou en Typescript**. 

Vous êtes complêtement libre visuellement d'utiliser ce que vous souhaitez (Bootstrap, Foundation ou autre). 

Vous devrez d'utiliser soit **Vue.js** soit **React**. 

#### Livrable

Vous devrez fournir l'ensemble du code source sur GitHub.

Votre site sera testée sur la dernière version de Chrome. La compatibilité IE n'est absolument pas requise. 