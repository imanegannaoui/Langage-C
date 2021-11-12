# Workshop 2 : Les instructions conditionnelles (If / Else)

## Objectif : 

- Utilisation des structures conditionnelles : if avec else, if sans else et switch.

### Challenge 1 : 

Traduire l’algorithme suivant en langage C. Quel est le résultat de son exécution
```
Algorithme CHALLENGE_1
Variables  nbr : Entier
Début
  Ecrire (‘donner un entier :’)
  Lire (nbr)
  Si (nbr<0) Alors
    Ecrire(‘le nbr’,nbr,’ est negatif’)      
  Sinon
    Si (nbr>0)Alors
      Ecrire(‘le nbr’,nbr,’ est positif’)      
    Sinon
      Ecrire(‘le nbr’,nbr,’ est nul’)      
    Finsi
  Finsi 
Fin
```

### Challenge 2 : Affichage Température

Ecrivez un programme qui demande la température en Fahrenheit et la transforme en degré Celsius et affiche la sensation ressentie (très froid, froid, chaud, très chaud)

La formule : C = (F-32)/1.8

### Challenge 3 : Paire ou Impaire

Ecrivez un programme qui demande un nombre et affiche si ce nombre est pair ou impair

### Challenge 4 :

Ecrivez un programme en C qui vérifie si un caractère saisi par l'utilisateur est une voyelle ou non en utilisant l'instruction `switch case`.

### Challenge 5 :

Ecrivez un programme C pour calculer la somme de deux valeurs entières données. Si les deux valeurs sont identiques, il renvoie le triple de leur somme.

### Challenge 6 : Equation deuxième degré

Écrivez un programme C qui permet de calculer les solutions possibles d’une équation 2ème degré.

### Challenge 7 : Programme guidé par menu pour convertir l'année

Ecrivez un programme C piloté par menu pour convertir une année donnée en,

1. Mois
2. Jours
3. Heures
4. Minutes
5. Secondes

Pour plus de simplicité, n'incluez pas l'année bissextile (sauf si vous êtes courageux pour le faire).
1 an = 365 jours
1 mois = 30 jours

### Challenge 8 :

Ecrivez un programme pour vérifier si le nombre donné est positif, négatif ou nul.

Si le nombre est inférieur à zéro, alors le nombre est négatif et si le nombre est supérieur à zéro, alors le nombre est positif. Si les deux conditions sont fausses, le nombre est égal à zéro.

### Challenge 9 :

Écrire un programme C  qui décide la mention d’un élève dans une école à partir de sa moyenne. Cet élève doit avoir: 
- la  mention  «passable»  pour  une  moyenne  supérieure  ou  égale  à  10  et inférieure à 12; 
- la  mention  «Assez  bien  »  pour  une  moyenne  supérieure  ou  égale  à  12  et inférieure à 14;
- la  mention    «Bien»  pour  une  moyenne  supérieure  ou  égale  à  14  et inférieure à 16;
- la mention «Très bien» pour une moyenne supérieure ou égale à 16.

### Challenge 10 : 

Écrire un programme C permettant de lire la valeur de la température de l'eau et d'afficher son état : 
- Glace si la température est inférieure à 0, t≤ 0.
- Eau si la température est strictement supérieure à 0 et <100, 0 < t ≤ 100.
- Vapeur si la température est strictement supérieure à 100, 100 < t.
