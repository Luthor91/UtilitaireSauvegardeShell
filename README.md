# UtilitaireSauvegardeShell

## Sera fait bientôt 
  Refonte entière de l'application pour qu'elle soit utilisable correctement


Pour installer cet utilitaire vous avez juste besoin de mettre le fichier dans un répertoire et de lancer la commande suivante : 

bash Chemin/Absolu/ou/Relatif/utilSave

L'utilitaire créer tout seul les fichiers dont il a besoin, vous pourrez aller dans le sous-menu "Paramètres" pour modifier les chemin ABSOLU utilisés.

Pour le sous-menu Paramètres, respectez à la lettre la "syntaxe" utilisé, si le chemin absolu fini par un "/", mettez le, si il n'est pas mentionnez, ne le mettez pas.

Les dossiers contenant les sauvegarde décompressés sont appelés "saveX" avec X un entier s'incrémentant tout seul, il risque d'y avoir quelques problèmes à cause de ça.
L'utilitaire supporte le fait qu'il y ai plusieurs archives du même nom, il cherchera un nom valide et la créera tout seul.
L'archive et la sauvegarde ont le même indice chiffré dans leur nom.

Lors de la compression d'un fichier, si l'application ne répond plus vous pouvez la quitter avec la combinaison de touches "Controle + C", 
veuillez regarder quand même dans le répertoire d'archive si l'archive est bien en cours de création.

L'utilitaire puisant ses données dans le fichier /tmp/Init au démarrage, si vous modifiez les valeurs du fichier après le démarrage, elles ne seront pas prises en compte.
L'utilitaire mettras une valeur par défaut en cas de "Reset" et si vous effacez le chemin inscrit dans le fichier /tmp/Init


!! ATTENTION !! 

La fonction de restauration de sauvegarde et de remplacament de fichiers n'est pas disponible mais n'entraine aucune erreur, sauf dans le fichier /tmp/LogsError
Le répertoire est bien créée mais est vide.
Le menu est mal affiché et à besoin qu'on mémorise les entrées pour être vraiment utilisé
