# CahierISNEtICN

Création de proof of concept  Jupyter / Jupyterhub à comparer à PythonEdu

## raisons de la création de ce dossier à l'intérieur des CahierDeProgrammes 

Le travail "meteo et climat : tremplin pour l'enseignement des sciences" s'appuie sur l'utilisation de nano-ordinateurs 

ou objets connectés et sur l'outil jupyterhub fournissant un serveur de sessions Jupyter.  


Les cahiers de ce dossier ont pour objectif d'assurer une formation pour des enseignants de mathématiques 

qui dans un premier temps ne souhaitent pas utiliser l'infrastructure d'exploitation de capteurs météo ou autres (sons, UV, etc) 

pour aborder la programmation en seconde. 

Tout le reste du dispositif et de la démarche Tremplin restent exploitables.


## Le cas de l'implémentation au Lycée Corneille et au lycee Camille Saint Saëns de l'académie de Rouen


Dans l'académie de Rouen l'arrivée de la programmation python en seconde génère un changement de positionnement 

des équipes de mathématiques, il semble essentiel de présenter jupyter notebook  et jupyterhub dans la mesure où 

ces outils sont largement utilisés dans la communauté scientifique et dans l'enseignement supérieur et qu'ils ont été 

testés dans le projet Tremplin. 

Ces outils  sont reconnus comme puissants et stables. 


## Contenu des cahiers 


Un cahier qui exploite le module Geopy : Objectif, générer une table ou un fichier qui permette quand on travaille avec des établissments de créer la ressource pour faire un shapefile dans QGIS.
Deux fichiers sont liés à ce livret, lieux.csv et lieux.db

Un cahier qui présente les balises markdown : ne sert pas à grand chose mais évite le passage par l'excellente page de github le va et vient entre "ressource en ligne" et "cahier" ne semblant pas aller de soi pour les usagers testeurs.

Un cahier Latex : Même chose que pour markdown mais j'ai parlé de Jupyterhub à Corneille et du coup le Latex semblait être une accroche  pour les profs de prépa et leurs élèves.

Un Cahier lié au projet Amiens PythonEdu : Ce projet a failli conduire
à l'enfermement de mon bahut dans une installation d'un .exe mais il semble que les exercices que contient leur pdf aient du sens .... pour montrer l'intérêt de Jupyterhub j'ai reproduit le Chapitre 1.
le fichier lycee.py est un module qui contient les fonctions utilisées par l'équipe d'Amiens.