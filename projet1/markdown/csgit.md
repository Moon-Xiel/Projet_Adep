# **Cheat Sheet Git** (version française) #

## _Configuration_ ##

Ajouter un nom
git config --global user.name "[nom]"  
Ajouter un email  
git config --global user.email "[monemail]"

## _Créer un nouveau repo_ ##

cd [nomdudossier]
git init

## _Cloner un repo déjà existant_ ##

git clone [url]

## _Ajouter ou Retirer des fichiers_ ##

Montrer le status du fichier et son index  
git status

Indexer un fichier
git add [nomdufichier]

Ajouter tous les fichiers du dossier dans l'index
git add .

Supprimer un fichier
git rm [nom.format]

## _Les "commit"_ ##

Commit tous les fichiers de l'index dans le répertoire local
git commit -m "message"

## _Historique_ ##

Montrer tous les commit
git log
Montrer qui a modifié le fichier 
git blame [nom.format]	

## _Les dépôts à distance_ ##

Lister les dépôts à distance
git remote 
Ajouter un dépôt à distance et lui donner un nom
git remote add [nom] [url]
Afficher les infos d'un dépôt distant
git remote show [nom]


## _Les branches_ ##

Liste des branches  
git branch  
Changer de branche  
git checkout [nomdelabranche]
Créer une branche  
git branch [nom]  
Supprimer une branche  
git branch -d [nom]

## _Les fusions_ ##
Fusionner une branche dans la branche actuel  
git merge [nomdelabranche]

