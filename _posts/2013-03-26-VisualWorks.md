---
layout: post
tags: [ VisualWorks, Smalltalk ]
---

Installation VisualWorks
-------------------------------
* Inscription sur le site cincomsmalltalk.com
* Téléchargement du .iso (~640 Mo)
* [Vidéo d'installation](http://www.cincomsmalltalk.com/casts/stDaily/2009/smalltalk_daily-09-10-09-lg.mp4)
* [Pour monter le .iso comme un disque sous Windows](http://www.slysoft.com/en/virtual-clonedrive.html)
* Lancement automatique ou manuel de
installWin.bat
(installable aussi sous Linux ou Mac)

Lancement de VisualWorks 
-------------------------------

[Les liens pour débuter](http://www.cincomsmalltalk.com/main/products/visualworks/follow-up/)

[Notamment, comment utiliser une image particulière, une fois le runtime installé](http://www.cincomsmalltalk.com/casts/stDaily/2009/smalltalk_daily-09-11-09-lg.mp4)

Une fois le runtime installé sous Windows, une entrée de menu permet de le lancer (VisualWorks Projects)
Le premier lancement indique qu'aucun projet n'existe, et indique l'endroit ou les projets sont stockés.

# Créer un projet dummy pour tester
* création d'un sous répertoire dummy sous D:\Users\xxx\Documents\VisualWorks Projects\
* création des fichiers dummy.im (image bytecode)
* création d'un fichier dummy.cha (code source des modifications)
* Ouverture de l'enviroonnement VisualWorks avec tous les outils (browser, transcript, ...)


# Projet Existant
Si on dispose de ces fichiers pour un projet existant, il suffit donc de les recopier au même endroit
* au lancement, le nouveau projet apparait. Si il a été créé avec une version précédente de VisualWorks, un avertissement apparaît
* Dans la fenêtre d'accueil File/Set VisualWorks Home / Paste Current / Apply

Utilisation de VisualWorks 
--------------------------------

# Navigation dans le code
Le 'System Browser' est l'outil principal pour naviguer dans le code.
4e icone en partant de la gauche 'Open a System Browser'
* La zone 'Find' permet de rechercher des éléments (classes) par leur nom  ou une partie de leur nom (ex: HTML)

# Recherche dans le code

* Il est aussi possible de faire une recherche textuelle dans le code :
 Sélectionner les classes ou packages désirés (CTRL A pour tous) 

Onglet 'Code Search', 'Search string'

L'outil va alors ouvrir une fenêtre de toutes les méthodes contenant le texte recherché (Case sensitive si option cochée)

Certains messages d'erreur peuvent survenir si on n'a pas accès au code source des classes recherchées. (ignorer)

Une fois la recherche terminée, il est possible d'exporter la liste des méthodes concernées dans un fichier .csv (Method / Export CSV). Le fichier est généré dans le répertoire de travail.

PACKAGE;VERSION;NAMESPACE;CLASSE;METHODE

Le renommer avec l'item recherché (ex: "BODY Export recherche Packages 2013-03-26 11-36.csv" pour la recherche de BODY), éventuellement purgé des éléments non souhaités (ex: PACKAGE BODY pour des méthodes SQL alors que l'on cherche BODY pour la génération HTML)


