# 5 - Application Allo Vegan (mobile hybride web)

#### Temps estimé

Entre 2 et 4 heures

#### Enoncé

Vous ferez **une application à destination des mobiles** dont l'objectif est de faire découvrir des restaurants vegans autour de chez vous. Cette application peut soit être réalisée avec *Ionic*, soit *Cordova*.

Pas besoin d'héberger un serveur, pour trouver la liste des restaurants, il suffit d'invoquer cette URL en remplaçant les valeurs de `VOTRELATITUDE` et `VOTRELONGITUDE` :

https://xlmd94l53b.execute-api.eu-west-2.amazonaws.com/api?lat=VOTRELATITUDE&long=VOTRELONGITUDE

Cette URL renverra les 10 restaurants les plus proches (les données sont générées aléatoirement ici, donc pas de persistance entre deux chargements). Attention, la documentation fournie par ce service n'est pas très fournie.

L'application devra géolocaliser l'utilisateur et lui permettre de voir sur une carte les différents restaurants autour de lui avec une fiche plus détaillée disponible.

#### Outils disponibles

Vous devrez développer en **Javascript (ES6) ou en Typescript**. 

Vous êtes complêtement libre visuellement d'utiliser ce que vous souhaitez (Bootstrap, Foundation ou autre). 

Il est recommandé d'utiliser **Ionic** et/ou **Angular**. 

Pour le module de carte, vous pouvez utiliser ce que vous voulez.

#### Livrable

Vous devrez fournir l'ensemble du code source sur GitHub.

Les applications mobiles devront fournir un APK qui sera testé sur un *Android 8*.

Eventuellement, votre application pourra également être testée en mode navigateur.