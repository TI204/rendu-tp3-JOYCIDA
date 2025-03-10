 TP3 - Branches et Fusion

Exercice 1 : Création et navigation entre branches

- Que se passe-t-il si vous essayez de supprimer une branche sur laquelle vous êtes ?

Si on tente de supprimer la branche active, Git renvoie un message d'erreur interdisant la suppression. On doit d'abord se déplacer sur une autre branche avant de pouvoir la supprimer.


- Comment voir les différences entre les branches main et feature-1 ?
On utilise la commande suivante pour comparer les modifications entre deux branches :
git diff main feature-1
Cela affiche toutes les différences entre les fichiers des deux branches.
