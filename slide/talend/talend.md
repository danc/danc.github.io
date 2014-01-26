title: Talend
author: Daniel Cortinovis
footer: Talent : Présentation
subfooter: Daniel Cortinovis - Pierre Germain

%css

body {
  background-image:         url(SII-Signature-mail-rennes.jpg);
  	background-repeat: no-repeat;
//	background-position: 940px 540px;
	background-position: 940px 40px;
}
.step {
  width: 1200px;
  height: 600px;
  padding: 40px 60px;

  font-size: 48px;
  text-align: center;

  opacity: 0.3;
}

%end

# ![Talend](talend_logo.png)

# ![Talend](talend_logo.png)

<div style="float:right;"><img src="solution-etl-for-analytics-diagram_1.jpg"></img></div>

  Historique

- **Talend** , société française, en fort développement aux US
- Outil de type **E**xtract, **T**ransform, **L**oad (ETL)
- Outil opensource à la base + plateformes professionnelles
- Plusieurs publics : [Communautaires](http://www.talendforge.org) _ET_ [Professionnels](http://www.talend.com)



# ![Talend](talend_logo.png)
  Evolutions
  
- Devient un outil de gestion des données au sens large (Data Management)
	- Data integration
	- Data Quality
	- Master Data Management (MDM) : gestion de données de référence
	- Big Data
	- ESB (Enterprise Service Bus) 

 

# Usages 

  A quoi ça sert ?

![automatisation](solution-synchronization-diagram_1.jpg)

# Usages
 
  A quoi ça sert ?

Cas d'école : 

- Des données client dans la base client
- Des données techniques dans la base ... technique
- Des données de facturation dans la base de facturation
- lien commun : identifiant client

- Problème : Des équipements facturés n'ont pas été livrés, le client n'est **pas** content ...




# Usages 


Solutions possibles :

- Plonger dans les différentes bases, faire des exports excel, 
- Analyser, et désigner le coupable
- A faire tous les mois ? vraiment ???
- Penser à la durée de traitement manuelle, aux coûts dérivés de cette recherche, 
- On n'a pas vraiment traité la cause du problème : la cohérence entre les différentes bases


# Qualité de données

- La qualité de données a besoin d'indicateurs
- La qualité de données a besoin d'être éprouvée en permanence
- Elle a donc besoin d'être industrialisée / automatisée

- Elle peut fournir une boucle de rétroaction (correction des données source)

![automatisation](solution-synchronization-diagram_1.jpg)

# Constats   
<div style="float:right;width:50%;"><img src="screenshot.309.png"></img></div>

- Orange constate que les problèmes de qualité de données sont coûteux :

   - contentieux clients
   - service client 
   - temps passé à résoudre des problèmes, 
   - à retrouver des informations pertinentes
   - nécessite une expertise technique 

- estimations : plusieurs M€
- La complexité d'un SI implique la mise en place d'une _gouvernance des données_

- Investissement dans un programme transverse (IMADAQ) 

# Talend : aperçu 

<img src="screenshot.276.png" alt="Aperçu" /> | ![ex](screenshot.287.png)

# Talend : aperçu 

![tMap](screenshot.294.png)

# Talend : vue technique

* Générateur / Compilateur de code *Java*
* Basé sur _Eclipse_
* Multiples composants prédéfinis

![lookup2](screenshot.291.png)

# Talend : vue technique


* Entrées : multiples sources de données

          Fichiers, Databases, json, xml, ...
* Transformations et analyses des flux de données ![lookup](screenshot.289.png)

          Jointures, filtrages, unicité, doublons, aggrégations, ... 
* Sorties : fichiers, bases de données, mails, ...



# Talend : vue technique

Connecteurs vers de grand nombres de base de données 

- Relationnelles (MySQL, Oracle, ... )

- Big Data (Hadoop, NoSQL, TeraData, MongoDB ...) 

- SAS

# Talend : vue technique

Solution packagée, progiciel complet
- La base opensource est déjà très complète 

Les plateformes Professionnelles ajoutent :

- une gestion de configuration Subversion ![svn](svn-square.jpg)
- une console d'administration web
   - Gestion des utilisateurs, projets, droits
   - Gestion des plateformes d'execution
   - Déploiement des jobs, scheduling
   - Supervision, Dashboard

![Monitoring](monitoring.png)

# Talend : vue technique

![schedule](screenshot.307.png)

# Talend : vue technique

- console de DataStewardship (réconciliation de données)
- ...

# Talend : offres packagées

- une intégration entre diverses briques ![Talend](talend_logo.png)

	Data Quality + Data Integration = Data Management platform

	DM + MDM = MDM platform
	
	DM + ESB
	
	DM + Big Data    
	
	...

- un modèle de licence original

	Souscription sur plusieurs années
	
	

# Talend : Data Quality 

![Data Quality / Profiling](screenshot.245.png)


![Business rules](screenshot.281.png) ![Business rules](screenshot.282.png)

# Talend : Data Quality 

![Data Quality / Profiling](screenshot.241.png) ![Business rules](screenshot.244.png)

![Business rules](screenshot.239.png)
