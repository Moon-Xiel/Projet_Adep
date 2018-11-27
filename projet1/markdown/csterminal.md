# **Cheat Sheet Terminal débutant/basique** (version Française) #

## _Les bases_ ##

- Lancer le terminal  
CTRL ALT t 
- Fermer le terminal  
exit
- Nettoyer le terminal  
clear ou CTRL l
- Auto completion  
TAB
- Répète la dernière commande   
!!
- Annule   
CTRL C 
- Installer   
sudo apt-get install [nom]  

## _Les permissions_ ##

- Ordre  
User/Group/All
- Types  
R: lire (4)  
W: modifier (2)  
X: execute (1)  
- Changer les permissions  
chmod

## _Les répertoires_ ##

- Montre le répertoire actuel  
pwd
- Créer un répertoire  
mkdir nom
- Se déplacer dans un dossier   
cd nom
- Aller dans un répertoire précécent   
cd -
- Aller dans un répertoire parent  
cd ..

## _Fichiers_ ##

- Créer un fichier  
touch nom.format
- Liste les fichiers  
ls
- Liste les fichiers + cachés  
ls -a
- Liste les fichiers + droits   
ls -lh
- Liste les fichiers (cachés) + droits  
ls -la

## _Déplacer/Renommer/Supprimer_ ##

- Déplacer un fichier vers un dossier  
mv nom.format document/
- Déplacer un dossier dans un dossier   
mv dossier1 dossier2
- Renommer un fichier  
mv anciennom.format nouveaunom.format
- Supprimer un fichier  
rm nom
- Supprimer un fichier avec demande de confirmation  
rm -i nom
- Supprimer un fichier sans demande de confirmation   
rm -f nom 
- Supprimer un dossier vide  
rmdir nom 
- Supprimer un dossier et son contenu  
rmdir -r nom





