# Answers of Remy Clivaz remyclivaz

## Basics
### Task 1
Les changements ont ete faits, mais ils n'ont pas ete ni commit ni push.
### Task 2
 - Le message propose en exemple signifie que les donness personelles ont ete modifiees dans le fichier answers.md
 - Non, il est impossible de creer un commit sans message
 - Le fichier modifie est enregistre dans l'historique, ainsi que les donnees de l'auteur
 - Non car le fichier n'a pas encore ete push sur git
### Task 3
Nous avons desormais 2 unstaged files et lorsque l'on clique sur le depot actuel, 1 untracked files est affiche
### Task 4
Quand on revient au commit: Initial commit , on voit le projet tel qu il etait au tout debut : seuls les premiers fichiers sont presents. On est en mode detache, donc on ne travaille plus sur une branche. En revenant au dernier commit (par exemple via main), on retrouve l etat actuel complet du projet.
### Task 5
Le depot local est la copie de votre projet stockee sur votre ordinateur, ou vous travaillez directement. Le depot distant, lui, est une version du projet hebergee sur un serveur (comme GitHub) pour partager et collaborer.
Si vous supprimez le depot local, vous perdez tout votre travail sur votre machine, mais le depot distant reste intact et vous pouvez recuperer le projet en le clonant a nouveau.
### Task 6
Non, le depot original qui a ete forke n a pas ete modifie car toutes les modifications sont faites uniquement sur ta copie (ton fork) et ton depot local.
Tant que tu ne fais pas de pull request et qu elle n est pas acceptee, le depot original reste identique a sa version initiale.
## Gitgraph

### Task 7
1. nom de la branche
2. hash de commit
3. message de commit
4. auteur du commit
5. tag
6. dernier commit
7. branche secondaire (feature-auth)
8. last commit de branche initiale
9. branch secondaire (develop)
10. commit initial

![Gitgraph](img/gitgraph.svg)