Authors :
=========

`Abir Bezzazi, Youness Fahmi et Mohamed Kouriat`

**************************************************************************************************

Objectifs du Projet
===================================

**************************************************************************************************
Le but de ce projet est de réaliser le jeu vidéo Starship mais en plus simple. Ce jeu consiste à détruire des soucoupes volantes sortant par la droite du canvas du jeu par un vaisseau 
émettant des tirs. Le joueur peut contrôler les déplacements de ce vaisseau qui se situe à gauche du canvas.
**************************************************************************************************

Récupérer le projet
===========================

**************************************************************************************************
Pour la récupération du projet, vous devez cloner ce dépôt en tapant la commande suivante :

**git clone https://github.com/bloomabir/Starship.git**

dans un terminal et récupérez le dossier nommé **fichiers-jeu_-starship-beta**.

**************************************************************************************************

Comment produire le bundle
===========

**************************************************************************************************
Dans un **Terminal**, vous vous placez à la racine du projet 
et vous tapez cette commande : **npm install**

ceci permet l'installation de toutes les dépendances décrites dans package.json.

Puis ensuite, toujours dans le terminal, vous tapez la commande : **npm run build**

pour l'exécution des commandes spécifiées dans build. Ceci vous créera le dossier *dist* et contiendra 
les dossiers correspondants aux différents loader (ici dossier *images* pour 
les images et *scripts* pour le fichier **bundle.js**) ainsi que le fichier **index.html** 
nécessaire à l'exécution de l'application sur le navigateur.

**************************************************************************************************

Exécution du projet
===================

**************************************************************************************************
Ouvrez le fichier **index.html** qui se trouve dans le dossier *dist* dans un des navigateurs suivants **Firefox / Google Chrome / Microsoft Edge** .

**************************************************************************************************

Quelques Remarques
==================

*L'appel de la methode stop() dans start() c'est pour éviter que les soucoupes se deplacent très très vite.*

**************************************************************************************************
