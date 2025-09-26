# Algebre Vectorielle MAT-0130-

## Définitions

- Une matrice est un tableau de nombres.
Notation : A, B, C …

- Le format ou la dimension d’une matrice est le nombre de lignes par le nombre de colonnes.......
Notation : Dim ( ) A

- Les nombres composant une matrice sont appelés éléments
Notation : a<sub>ij

- Le pivot d’une ligne est le premier élément non-nul de cette ligne.
- Une matrice échelonnée est une matrice présentant les caractéristiques suivantes :
  - Le pivot de chaque ligne est situé à droite du pivot de la ligne précédente.
  - Si la matrice possède des lignes nulles, elles doivent se situer sous les lignes non nulles.
 
- Une matrice échelonnée réduite est une matrice présentant les caractéristiques suivantes :
  - C'est une matrice échelonnée.
  - Chaque pivot vaut obligatoirement 1.
  - Tous les éléments d'une colonne contenant un pivot sont nuls (excluant le pivot, bien sûr!).
 
## liste de matrices particulières
- Une matrice ligne est une matrice ne comportant qu’une ligne, donc de format 1Xn  A=[1 2 3 4]<sub>1x4
- Une matrice colonne est une matrice ne comportant qu’une colonne, donc de format mx1 . A=[]<sub>3x1
- Une matrice carrée est une matrice qui comporte le même nombre de lignes et de colonnes. Une matrice carrée de format nxn ordre n
- La diagonale principale d’une matrice carrée A d’ordre n est formée des éléments a<sub>ii
- La trace d’une matrice carrée A d’ordre n, notée Tr (A), est la somme des éléments de la diagonale principale a<sub>ii
- Une matrice nulle est une matrice dont tous les éléments sont nuls. La matrice nulle de format mxn est notée par la lettre O<sub>mxn
- Une matrice triangulaire supérieure est une matrice carrée dont tous les éléments situés en-dessous de la diagonale principale sont nuls . (A[a<sub>ij</sub>]<sub>nxn</sub> ou a<sub>ij</sub> = 0 pour tout i > j)
- Une matrice triangulaire inférieure est une matrice carrée dont tous les éléments situés au-dessus de la diagonale principale sont nuls (A[a<sub>ij</sub>]<sub>nxn</sub> ou a<sub>ij</sub> = 0 pour tout i < j)
- Une matrice diagonale est une matrice carrée dont tous les éléments qui ne sont pas situés sur la diagonale principale sont nuls 
   - a<sub>ij</sub> = k<sub>i</sub> si i=j
   - a<sub>ij</sub> = 0 si i!=j   
- Une matrice scalaire est une matrice diagonale dont tous les éléments de la diagonale principale sont égaux.
  - a<sub>ij</sub> = k si i=j
  - a<sub>ij</sub> = 0 si i!=j

- Une matrice identité est une matrice scalaire dont tous les éléments de la diagonale principale sont des « 1 ». La matrice identité de format nxn est notée par la lettre i<sub>n</sub>
- Une matrice symétrique est une matrice carrée pour tout i et tout j. En d’autres termes, les éléments symétriques par rapport à la diagonale principale sont égaux. a<sub>ij</sub> = a<sub>ji</sub>
- Une matrice antisymétrique est une matrice carrée pour tout i et tout j. En d’autres termes, les éléments symétriques par rapport à la diagonale principale sont égaux, mais de signes contraires. a<sub>ij</sub> = -a<sub>ji</sub>



## Chapitre 2 : Opérations sur les matrices

- Addition de matrices  pour pouvoir additionner ou soustraire deux matrices, celles-ci doivent au départ avoir le même format
- 






