
INTRODUCTION MODULE PHP
FORMATEUR : J.
CR : M. MASSON
20.01.2020

#I. Présentation du formateur#

Jérôme XX présent dès la première formation "WebDev". Intervient en PHP & en Javascript et sur le suivi des apprenants.
A commencé à l"âge de 10 ans à s'intéresser à l'informatique, il y a donc 40 ans.
Travaille pour deux structures (PHP & JS)

##I. CONSEILS##

Question : Quel est le meilleur ami du développeur ?
Réponse :
son cerveau
+ Git
+ le bon IDE

En effet, le meilleur dev. est celui qui sait gérer son cerveau. Chacun va aller aux limites de son cerveau et chacun va pousser ses limites. ► Il est important d'apprendre a  se connaitre soi-même c'est-à-dire :
- d'identifier les moyens qui nous aident le plus à comprendre ( texte, dessin ou visuels, vidéios, livres, échanges oraux, exercices, ...)

Un développeur est employé pour son cerveau.  La bonne question à se poser : quelle stratégie vais-je mettre en place.

Chaque formateur à sa vision et ses propres manières de faire.  Ils vont se succéder sur ce module.
Il faut exploiter cette variété d'approches.
Il faut se faire confiance, faire confiance, en ses capacités.

Votre mental explique le formateur risque de connaître des fluctuations, des moments de  baisses car on casse, on défait sans cesse pour améliorer et refaire. Cela correspond au processus de développement et aussi d'apprentissage.

Il est normal de pleurer, de s'énerver, d'avoir envie et besoin de quitter la pièce. Car cet apprentissage est a l'image d'une montagne à gravir.
Jérôme dit que, pour lui, les moments les plus durs ont été les notions MVC.

Au cours de la formation, le cerveau va établir des parallèles entre les langages et les notions.
Il faut privilégier la logique et non la syntaxe.

La courbe d'apprentissage


Le schéma montre que cette courbe fonctionne par paliers successifs.
Le palier correspond à un moment de confusion, de remise en question, de doutes. En effet lors de cette phase d'apprentissage, le cerveau effectue différents travaux en arrière-plan.
L'état mental qui en résulte au niveau conscient est désagréable. Il est donc normal de se sentir mal. Quelqu'un qui ne connaît pas de gêne est : soit un génie, soit n'assimile pas.

Il est donc important de ne pas chercher à sauter les étapes. Il faut aller à son rythme.

En résumé : module complet, long qui paraît répétitif, mais qui est essentiel.

Question : pourquoi certains langages sont-ils plus utilisés que d'autres ?
Le développement d'un langage se fait de façon empirique. Ce langage réponds a des besoins et va évoluer en conséquence. Prenez par exemple python. Un matheux s'est mis à utiliser python et à développe une très grande librairie. Du fait de cette librairie d'autres développeur se sont mis à utiliser python et la communauté n'a fait que croître et s'enrichir de nouveaux éléments.

II. PHP

Notions préalables : internet

Programme du module
1. PHP de base
2.  base de données
3. Objets
4. MVC introduction du concept
+ Framework : application

Objectif / Fil rouge du module
. Faire un site web e-catalogue de produits
. Permettre au client de constituer un panier et de passer commande.

Le module PHP est très important car :
- Le plus gros module en durée au cours de la formation.
- Les concepts du PHP valent pour tous les langages
-  PHP est extrêmement simple pour les débutants, mais offre aussi des fonctionnalités avancées pour les experts.
- Donc très simple au début (facile pour tous) et très compliqué/élaboré à la fin ( tout le monde souffre).

Au début du HTML il fallait utiliser le langage C avec des script CGI pour exécuter le HTML sur le serveur.
Le PHP a permis d'articuler les choses.

Le nom donné au PHP et une feinte de développeur en référence au langage récursif.

Architecture client-serveur
Serveur ou ferme de serveur (hardware - machine physique).
La machine physique fait tourner plusieurs soft le serveur va  travailler pour un utilisateur comme pour un million d'utilisateurs.

Chaque client va voir la même page HTML.
Pour diffuser des contenus différents il faut ajouter des langages de programmation.

Pour interagir avec le client il y a deux façons :
- Côté serveur en PHP (gestion de données, gestion des API...)
- Côté client en javascript, interaction avec le navigateur.

Les différentes tâches sont réparties entre serveur et machine cliente.
Le PHP va gérer :
- le traitement des données
- l'affichage d'un catalogue.

Lorsque je vais sur l'adresse URL de mon profil FB, le serveur va afficher sur mon client la page Facebook.

Le serveur ne parle que le protocole HTTP. Au travers de ce tube qu'est le protocole\* HTTP,  le serveur envoie du HTML, du JavaScript, du son ... mais le code PHP reste, lui, côté serveur.

Http : Hyper Text Transfer Protocol
HTTP est une norme très simple. HTTP envoie par exemple des messages d'erreur.
Le protocole fait partie des outils à connaître.

Installation

Pour développer il faut reproduire l'environnement (stack serveur ou empilement des différentes couches) sur notre machine c'est-à-dire simuler un serveur en local sur notre machine.
Ce stack va comporter :
- un navigateur
- un IDE

----------

Ressources PHP sur le web
Forum, tuto, blog, librairie

Attention :
Les réponses obtenues sont au plus proche de la sémantique que j'ai moi-même utilisée dans la requête.
Les réponses les plus cliquées sont placés en première position (après les sections réservées aux liens publicitaires).

La syntaxe de la requête est importante. La capacité a effectuer des recherches (syntaxe, itération, filtres...)  est une compétence à part entière, qu'il ne faut pas négliger.

Pour évaluer la pertinence des résultats :
. Regarder la date
. Vérifier le numéro de version du logiciel ou de l'applicatif
. Bien lire le manuel de PHP (sur php.net tenue à jour. Il détaille toutes les fonctions tous les problèmes connus y sont répertoriés (troubleshooting).
. Pour assembler un programme il faut le décomposer en une série de questions.

-----------

Git  (En résumé)
1. Tous les problèmes sont des problèmes Git.
2. Si problème : 
reverse base ou gestion du conflit.
3. J'ai déjà une partie qui fonctionne et je veux essayer un nouveau truc :
- Je crée une branche. si ok je merge.
4. On travaille à deux :
2 branches. Si ok : Merge.
5. Je veux tenter un truc :
Option A :  une branche A
Option B : une branche B
Ensuite je merge.

Le soir je commit pour sauvegarder mon travail sur le serveur distant.

----------

Synthèse des 4 présentations effectuées :
Il est question à chaque fois de :
. Fichier de configs
. Fichier de logs
Pourquoi ?
Parce que les choses sont rangés à certaines places.
Il faut retrouver la place de chaque chose.

C'est à vous ... 🙂
	
	
	
