# git-demo
Démonstration de Git pour les membres du groupe coma (Laboratoire d'imagerie biomédicale).

Bonjour à tous,

Voici quelques exercices pour vous entraîner sur la leçon du mardi 5 avril :

## Exercice n°1
1. Vous trouverez un fichier intitulé "participants.txt" ; ouvrez-le et ajoutez-y une ligne avec votre nom (ou votre surnom/alias).
2. Enregistrez les changements dans votre éditeur de texte.
3. Utilisez la commande `git status` pour constater que Git a repéré un changement dans ce fichier.
4. Visualisez les changements à l'aide de la commande `git diff participants.txt` (et/ou à l'aide du GUI).
5. Utilisez la commande `git add participants.txt` pour ajouter ces changements au prochain commit.
6. Utilisez la commande `git commit -m "XXX"` avec le message que vous voulez à la place de `XXX`.
7. Utilisez la commande `git push origin master` pour envoyer ces changements sur le dépôt distant.

## Exercice n°2
1. Dans votre dépôt local, créez un répertoire à votre nom (ou votre surnom/alias).
2. Ajoutez-y un fichier intitulé "bio.txt"
3. Écrivez un petit texte vous présentant succintement (ex. "Je m'appelle Dark Vador, et je n'ai pas tué son père").
4. Commitez ce texte (soit avec le GUI, soit en ligne de commande).
5. Envoyez les changements sur ce dépôt distant.

## Exercice n°3
1. Ajoutez une image de type png dans votre dépôt local.
2. Utilisez la commande `git status` (ou bien visualisez votre dépôt dans le GUI). Git a repéré qu'il y a un nouveau fichier dans le dépôt.
3. Créer un fichier intitulé ".gitignore"
4. Ouvrez-le à l'aide d'un éditeur de texte, et écrivez la ligne "*.png"
5. Commitez ce changement : `git add .gitignore` et `git commit -m "ajout d'un fichier .gitignore"`
6. Utilisez la commande `git status` (ou bien visualisez votre dépôt dans le GUI). Votre image n'apparaît plus dans les fichiers ajoutés.
7. N'envoyez pas ces modifications au dépôt distant, car cela risque de perturber les autres dépôts.

> Si vous avez des questions, n'hésitez surtout pas et envoyez-moi un mail !
