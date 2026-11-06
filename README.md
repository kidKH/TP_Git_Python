titre : TP_Git_Python

##PRESENTATION:

Ce projet s'inscrit dans le cadre du TP1 d'outils collaboratifs. L'objectif etait de creer un petit programme Python appele main.py, qui sert d'assistant de revision, et de gerer son historique de versions avec Git et GitHub.

##ETAPES:
le projet a 4 etape:
V1 : On a cree un simple message de bienvenue dans le code.
V2 : On a ajoute le prenom de l'utilisateur dans le code, puis on l'a envoye sur GitHub pour la premiere fois.
V3 : Quelqu'un a ajoute la matiere a reviser sur GitHub, et nous on l'a recuperee sur notre PC.
V4 : On a ajoute le temps de revision sur notre PC, puis on a renvoye le tout sur GitHub.


##COMMENT EXECUTER LE PROGRAMME:
comment lancer le programme:

on ouvre le dossier TP_Git_Python dans VS Code, puis on cliques sur main.py.
on cliques sur le bouton play (triangle) en haut a droite.
Le terminal s'ouvre en bas, et tu ecris ton prenom, la matiere et le temps en appuyant sur Entree a chaque fois.



##COMMANDES GIT UTILISES:

pwd : Affiche le dossier courant dans lequel tu te trouves.
git config : Configure ton nom d'utilisateur et ton e-mail globalement sur Git.
git init : Initialise un dépôt Git vide dans ton dossier local.
git status : Affiche l'état du dossier et des fichiers (modifiés, prêts à être validés).
git add : Prépare et ajoute le fichier main.py à la zone de staging pour le commit.
git commit : Enregistre une sauvegarde (un commit) des modifications en local avec un message.
git log : Affiche l'historique complet des commits du plus récent au plus ancien.
git branch -M main : Renomme la branche principale locale en main.
git remote add origin : Lie ton dossier local au dépôt distant sur GitHub via son URL.
git remote -v : Vérifie et affiche l'adresse URL du dépôt distant lié.
git push : Envoie et publie tes commits locaux sur GitHub.
git pull : Télécharge et fusionne les modifications distantes de GitHub vers ton PC.
