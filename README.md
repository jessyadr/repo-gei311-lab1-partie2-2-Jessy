Nom étudiant: ANDRIANANDRAINA Antsanirina Jessy
Code permanent: ANDA23620100

Partie 1: Collaboration sur un Repository

Cette partie du laboratoire nous a inité à l'utilisation de la plateforme Github. On a pu apprendre
à créer et cloner un repository sur Github, à créer des dossiers et des fichiers pour ensuite les
committer. Noua avons également appris à créer et travailler sur des branches, à collaborarer avec un 
membre d'équipe en modifiant et en comittant des fichiers. 
Nous avons également pu apprendre sur comment merger des modifications dans la branche principale, 
et visualiser et enregistrer des commits.


Partie 2: Situations Problématiques:

Pour cette dernière partie du laboratoire, nous avons pu rendre un projet local accessible via GitHub
pour la collaboration. Nous avons également pu gérer des problèmes liés à des commits non compilables 
et des merges non testés. Nous avons également utiliser les issues pour signaler et résoudre des
problèmes. 
Un issuer doit contenir un titre clair et concis, ainsi qu'une description détaillée du problème. 
Il doit également indiquer ce qui devrait être versus ce qui s'est passé réellement. Il faut 
également mentionner le commit problématique et le dernier commit fonctionnel.
Et pour terminer, nous sommes parvenus à revenir à une version fonctionnelle en utilisant 
l'historique des commits et git reset --hard.

A Noter:
Lors du retour vers le commit non problématique, cela supprimé toute la liste des commits qui 
étaient là avant. De ce fait, nous avons également dû utiliser git push --force origin car 
l'historique de la branche distante a été écrasée.

Git Cheat-Sheet:
Liste des commandes fréquemment utilisées ainsi que leur rôle respectifs.

-	Git clone : copier notre repository distant sur le serveur de github et 
le coller sur notre machine locale
-	Cd : naviguer dans le répertoire 
-	Mkdir (make directory) : créer un répertoire
-	Cd.. : retour en arrière d’un répertoire
-	Echo .. >> ….txt : écrire une chaine de caractère dans un fichier 
-	Git add - -a : utiliser tous mes fichiers prêts à être envoyer sur le répertoire distant github
-	Git Commit -m : attribuer un message à la modification qu’on vient de faire 
à l’intérieur de l’environnement de travail
-	Git push origin <branchname> : déployer les changements sur le répertoire distant, 
origin : le lien qui existe entre la machine locale et le répertoire distant, 
-	Git branch : pour voir les branches locales sur la machine locale
-	Git branch -r : pour ajouter les branches distantes
-	Git checkout – b nomdelabranche : créer une nouvelle branche locale 
et de changer vers la nouvelle branche créée
-	Git checkout nom_branche : pour changer de branche vers nom_branche
-	Git pull origin nom_branche: mettre les changements venant d’un répertoire distant sur un repo local
-	Git merge : fusionner des modifications d'une branche dans une autre
-	Git log : pour afficher l’historique des commits
-	Git reset -- hard <commit>: réinitialiser l'état du repository à un commit spécifique
-	Git init : initialisation d’un répertoire locale git
-	Git push --force origin <branchname>: pour forver l'envoi des modifications locales 
vers le repository distant 

En résumé, ce laboratoire nous a permis de nous initier et d'apprendre plus sur GitHub.
Il nous a également pousser à faire des recherches quand un problème survenait. De ce fait, 
nous sommes plus à l'aise avec la plateforme et maitrisons certaines commandes.
