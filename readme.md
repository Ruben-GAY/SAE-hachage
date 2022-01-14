### ALEXIS CAMPS - DORIAN GRASSET - RUBEN GAY - ISSIAKA CISSOKHO 📚


**SAE HACHAGE**

Vous trouverez dans ce repo notre travail sur la SAE Hachage.

---
### Sommaire
1. [Réponses aux questions](#réponses-aux-questions)
2. [Fichiers](#fichiers)

---
## Réponses aux questions

>**Question 1:**

Sachant que |S| est le nombre de mots différents du texte et U l'ensemble de toutes les chaînes d'au plus 30 caractères et qu'il y a 256 caractères possibles

`|U| = 256^30`

Lorsqu’on a au plus 32 caractères :

`|U| = 32^30`

>**Question 2:**

Supposons que U = [0,x], une des structures de donnée très simple respectant : 
- la propriété p2 = on voudrait que les opérations de base (insertion, suppression, recherche) soient très rapides, au sens où elles n’exécutent que très peu d’opérations (par exemple un nombre constant, c’est-à-dire borné par une certaine constante, ou logarithmique en |T|).

Est `le tableau de booléens`, qui lorsque la valeur sera présente dans le tableau renverra true, false sinon.

>**Question 3:**

On sait qu'un *octet* permet de représenter 2⁸ valeurs soit *256 valeurs différentes*.
Si on possède X possibilités de chaîne de caractères différentes, pour savoir combien il faut d'octets, on fait le calcul : X / (nombre de valeurs différentes pour 1 octet)
On obtient `256^32 / 256` qui est égal au *nombre d'octets* nécessaire pour stocker un élément de u.

>**Question 18:**

On doit trouver un nombre de multiplications pour convertir une chaîne s(k). Pour cela on calculera chaque terme (xi256^i) indépendamment. Pour un mot de taille k, on fait le calcul : `k*(k+1)/2` et on trouvera un grand nombre de multiplications.

>**Question 27:**

Dans le fichier "LeRougeEtLeNoir.txt" il y a `16280 mots` différents.

---
## Fichiers

- [x] Dictionnaires.java
- [x] HTNaive.java
- [x] LeRougeEtLeNoir.txt
- [x] ListeBigI.java
- [x] Maillon.java
- [x] randomWords.txt
- [x] randomWordsPetit.txt

