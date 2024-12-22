# Projet-PreIng2-BTC2-Onclercq-Roux
But du projet :

Ce programme python a pour but de générer automatiquement des graphiques à partir d'un dossier local type "csv" en y effectuant des filtrages de données. 

Utilisation du programme :

Pour utiliser ce programme python il faut d'abord vérifier que votre fichier source soit enregistrer dans le même espace que celui où vous avez sauvegarder ce programme, généralement dans l'espace téléchargement. 
Il faut aussi vérifier la présence des dossiers locaux dans votre ordinateur nommés "images", "input" et "output".  
Ensuite, il faut renseigner le nom du fichier à traiter, ligne 6 dans la variable "fichier_source", ainsi que dans les fonctions display (premier dossier),lignes 68, 174, 313.
Pour copier le fichier source dans le dossier "input", penser à écrire le nom du fichier à la ligne 9, dans la variable "dossier_destination".
Et, eventuellement, changer le nom des dossiers filtrés qui seront générés après le filtrage afin de ne pas les mélanger dans votre ordinateur si vous utilisez le programme pour différents fichiers sources, dans les fonctions display (deuxième dossier), lignes 68, 174 et 313.   
Enfin il suffit de lancer le code et les graphiques et dossiers filtrés générés seront directemnt copiés dans les dossiers "images", "output" et "input".

Limites de notre programme :

Ce programme comporte quelques limites. Premièrement il nécéssite la présence au préalable des dossiers locaux "images", "output" et "input" sur le disque dure de votre ordinateur.  
Deuxièmement, il faut que votre fichier source soit enregister dans le même espace que le programme ou alors rajouter le chemin pour le trouver dans notre programme.  
Troisièmement, si ce programme fonctionne quelque soit le nombre de souris, il ne fonctionne que sur les fichiers ayant le même nombre et ordre de colonnes que ceux fournis dans le cours.  
Et enfin le programme ne pourra générer les graphiques "violon" que si le "washout day" est renseigné en tant que 0 ou 1, comme dans les fichiers fournis.

