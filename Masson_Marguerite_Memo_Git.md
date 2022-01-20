
# Linux - Commandes de base 

## Première étape

**git clone** git clone (lien https..) 
permet de cloner le repository distant sur le répertoire local courant (pour pouvoir ensuite modifier les fichiers, à updater ensuite)

**cd ..**
remonte du répertoire courant au répertoire du niveau supérieur

**mkdir <FOLDERNAME>**
Créer un nouveau dossier (make directory)

**cd <FOLDERNAME>**
Naviguer dans un dossier existant (change directory)

**ls**
Lister les éléments dans un dossier
**ls -a** tous les fichiers et répertoires du répertoire courant (y compris les cachés).  
**ls -l** liste longue des répertoires et fichiers avec détails
**ls** : list. liste le contenu d'un répertoire
**l -h** : Affiche la taille des fichiers avec un suffixe correspondant à l'unité (K, M, G) 
**ls -lct** : Permet de trier les fichiers et répertoires par date de modification décroissante
**ls -alrt** liste longue des répertoires et fichiers avec détails y compris les cachés, les plus récents en bas de liste

**git init**
Activez Git pour initialiser le répertoire courant et que celui-ci trace les différentes versions (repository)

**git status**
Vérifiez l'état des modifications dans un dépôt. Git signale si un fichier a été ajouté.

**git add readme.txt** 
Pour ajouter le nouveau fichier et que ses révisions puissent être prise en compte par Git.

**git commit -m "Création du fichier readme"**
Pour soumettre (commit) des modifications à l'historique du dépôt en associant un court (m) message décrivant la nature de(s) la mise(s) à jour.

**git diff**
Pour afficher les modifications apportées aux fichiers

**git add <FILENAME>**
Ajouter un fichier au répertoire

**git add .**
Pour ajouter tous les fichiers modifiés d'un répertoire en un seul lot

**cd**  
permet de revenir au répertoire /home/utilisateur
**cd -**
permet de revenir au répertoire vu précédemmment
**cd ..**
permet de remonter au répertoire parent
**cd /**
permet de remonter à la racine

**man** : manual affiche les pages du manuel system pour la commande (help)

**mv** : move
Permet de déplacer ou renommer des fichiers et des répertoires
**mv monFichier unRep/**
Déplace monFichier dans le répertoire unRep

**cp** : copy
Permet de copier des fichiers ou des répertoires

**rm** : remove
**rm CeFichier** : Efface du répertoire courant le fichier CeFichier.
**rmdir** : : remove directory
Supprime un répertoire (vide). Attention à cette commande.


**mkdir** : make directory
**pwd** : print working directory. Affiche le répertoire de travail

**ln** : link. crée un lien symbolique vers un fichier ou répertoire.
 **grep** : Recherche (plein texte) une chaîne de caractères dans des fichiers 
**more** : affiche un fichier page par page
**chmod** : change mode. Modifie les permissions d'accès à un fichier ou à un répertoire.

**gitk** affiche le répertoire et les infos de versionning en GUI ( Graphic User Interface)

**CtrlC**
pour sortir quand on est bloqué.

+ user ... 
https://doc.ubuntu-fr.org/tutoriel/console_commandes_de_base

## BONNE PRATIQUE

- git init
- git remote
- git status
- git pull

git add
git commit
git push

si conflit MERGE :
Se parler entre collaborateurs
Un des collaborateurs modifie le fichier ou rep posant pb
puis refait la boucle. Jussqu'à ce que le conflit ait disparu.

## COLLABORATIONS ( Pull Request)

1. Lister les issues
2. Détailler les issues
3. Assigner les Issues
4. chacun fait son job
    5. Chacun renseigne l'issue avec un commentaire et la ferme
    6. Le dernier collaborateur du groupe ferme la liste d'issues
    7. Chacun renseigne aussi l'issue du projet global
8. L'administrateur ferme le groupe d'issues (et peut procéder au push en production).

## BRANCHES

A compléter
