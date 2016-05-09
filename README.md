# Cartes des d�partements 

Ce projet extrait la cartes de chaque d�partements fran�ais depuis l'archive hebdomadaire d'Open Street Map, selon la [m�thode propos�e 
Maxime R�sibois](http://www.portailsig.org/content/recuperer-des-donnees-openstreetmap-gdalogr)
 sur PortailSIG. 


# Contenu

Chaque d�partement est livr� sous forme d'une archive ZIP qui contient plusieurs couches cartographiques au fomat shapefile (le .doc de la cartographie) :
- places.shp : noms des villes ou des quartiers
- roads.shp : toutes les voies de passage de l'autoroute au chemin pi�ton
- buildings.shp : l'espace b�ti
- raillways.shp : les voies ferr�es
- waterways.shp :le r�seau hydrolique
- points.shp : une liste de point d�int�r�t
- natural.shp : zones vertes
- landuse.shp : occupation des sol
- admin-departement.shp : le d�partement

Par ailleurs, un fichier projet [QGis](http://www.qgis.org/fr/site/) tr�s sommaire est fourni dans l'archive, afin de visualiser la superposition des couches dans un outil libre.


# Installation et lancement

Ce projet n�cessite [tuttle](https://github.com/lexman/tuttle), un syst�me de build pour les donn�es.
Une fois que vous avez install� tuttle en suivant les instructions pour votre syst�me, vous pouvez lancer le traitement des donn�es avec a commande :

    tuttle run


# Licence
Les sources de ce projet sont sous licence MIT.

Si vous lancez ce projet les cartes obtenues seront sous licence ODbL qui impose un partage � l'identique et la mention obligatoire d'attribution doit �tre "� les contributeurs d'OpenStreetMap sous licence ODbL" conform�ment � http://osm.org/copyright