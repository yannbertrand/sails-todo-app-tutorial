# [Épisode 1] Installations et création du projet Sails

* [Retour au sommaire](./#Épisode-1-installations-et-création-du-projet-sails)

## Slide 1 - Titre

Pour commencer cette série, je vais vous présenter mon matériel et nous allons mettre en place notre environnement de développement.

## Slide 2 - Hardware

Au niveau hardware, je présenterai ces tutos sur mon **Macbook Pro** late 2014 mais vous pouvez bien entendu le suivre sans problème, que ce soit sur Windows ou sur Linux. Mon ordinateur tourne sous **Mac OS X Yosemite**.

## Slide 3 - Node.js

### Présentation

Pour utiliser le framework Sails, nous avons besoin de **Node.js**.

J'utiliserai la version 0.12.2. 

### Installation

Pour installer Node, il suffit de se rendre sur http://nodejs.org et de cliquer sur le bouton "install". Une fois le téléchargement terminé, l'installation est classique.

Pour vérifier que tout est bien installé, je vous conseille d'ouvrir un terminal et de taper les commandes :

1. `node -v` qui vous donne le numéro de la version de Node que vous avez installé puis
2. `npm -v` qui fait la même chose pour le gestionnaire de paquets de Node.js : npm

### Transition

Une fois Node.js installé, nous pouvons passer à l'installation

## Slide 4 - Sails.js

### Présentation

de **Sails.JS**. Ce framework MVC inspiré de Ruby on Rails nous permet de développer des applications modernes grâce une architecture orientée services. Il est particulièrement adapté pour créer un chat, un dashboard temps-réel, ou un jeu multi-joueurs. 

Pendant cette série de tutoriaux, je vais utiliser la version 0.11.0.

### Installation

Afin d'utiliser Sails à son plein potentiel, installons sa ligne de commande en tapant `npm install -g sails`. Cet outil nous permet de créer un projet Sails, pour y parvenir, tapez `sails new ToDoApp` pour générer l'architecture dans le dossier "ToDoApp". Déplacer vous dans ce dossier avec la commande `cd`, puis lancez le serveur en tapant `sails lift`. Nous pouvons dès à présent accéder à notre site web à l'url http://localhost:1337.

### Transition

Pour terminer ce premier épisode, voici l'éditeur de texte que j'utilise :

## Slide 5 - Sublime Text

### Présentation

**Sublime Text**. Ce logiciel sophistiqué me fait gagner beaucoup de temps grâce à ces nombreux raccourcis, il a en plus le mérite d'avoir une très jolie interface. J'utiliserai pour ma part la version 3.

### Installation

Pour l'installation de Sublime Text, il faut se rendre à l'adresse http://sublimetext.com/3 puis choisir la version correspondante à notre OS.

### Transition

## Slide 6 - Fin

Tout est prêt, je vous invite de suite à passer à l'épisode suivant pour configurer notre serveur.

## Navigation

* ~~[Aller au script de l'épisode 2](../Ep2/SCRIPT.md#Épisode-2-création-d-une-ressource)~~
* [Aller au sommaire de l'épisode 2](../Ep2#Épisode-2-création-d-une-ressource)
* [Retour au sommaire](./#Épisode-1-installations-et-création-du-projet-sails)