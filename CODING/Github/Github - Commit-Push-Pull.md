1)      Pour commit :    **git commit**        (C0 – C1 -C2)

2)      Pour créer une branche :   **git branch newImage** (newImage = nom de la branche)

3)      Permet d’enregistrer les modifications sur la branche choisies :

**Git checkout newImage; git commit**

4)      Pour fusionner la branche choisie avec le main :   **git merge bugFix**

5)      Après avoir fusionné la branche choisie avec le main. On déplace « bugFix » au main :

**Git checkout bugFix; git merge main**

6)      Retourner sur la branche main :   **git checkout main** 

7)      Au lieu de réunir une branche sur le main avec « git merge », on utilise « **git rebase main** » pour faire croire que les deux branches ont toujours été l’une après l’autre (et pas l’une développé en parallèle de l’autre). On déplace ensuite le main sur la branche en dessous avec « **git rebase bugFix** » (bugFix = nom de la branche en dessous).

8)      Faire apparaître le « HEAD » :

**git checkout C1; git checkout main; git commit ; git checkout C2**

9)      Pour détacher « HEAD » (le rattacher à un commit, et non pas à une branche) :

**git checkout C1**

10)  Revenir d’un commit en arrière : **^**

11)  Revenir de deux commit en arrière de main : **main^^**

12)  Revenir de plusieurs commit en arrière **: ~<num> (num=numéro)**

13)  Par exemple : **git checkout main^** (On déplace le HEAD sur le premier parent de main)

14)  Déplacer le main à 3 branches en arrière du head :

**git branch -f main HEAD~3**

