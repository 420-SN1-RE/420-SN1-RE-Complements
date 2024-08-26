## Exercices supplémentaire Semaine 1

### Question 1
Bon, ce n'est pas un problème de nature scientifique mais c'est pratique.
Vous allez faire des achats pour $120. La personne à la caisse vous annonce que vous avez droit à un rabais de 15%
Écrivez un petit programme qui affiche le montant original, le rabais et le montant final.  
Par exemple
>Le montant original est  120
>Le rabais est  18.0
>Le montant final est  102.0
  
Si vous voulez être plus interactif, vous pouvez utiliser
>montant = float(input("Saisir le montant: "))  
>rabais_pourcentage = float(input("Saisir le pourcentage du rabais (sans le %): "))

Vous allez obtenir ceci
>Saisir le montant: 120  
>Saisir le pourcentage du rabais (sans le %): 15  
>Le montant original est  120.0  
>Le rabais est  18.0  
>Le montant final est  102.0  

### Question 1.5
Calculez le pourboire à donner sur le montant de la facture (un pourcentage du montant de la facture avant taxes). Utilisez 100 pour le montant et 15 pour le pourcentage du pourboire. Donc pour un montant de 100$, le pourboire serait $15.


### Question 1.5b
Complétez la question 1.5 en calculant le montant final de la facture après taxes, i.e. la somme de 
+ montant de la facture 
+ TVQ (9,975%) sur le montant original
+ TPS (5%) sur le montant original
+ pourboire (un pourcentage du montant original)

Si vous utilisez 100 et 15, vous devriez obtenir
>Le montant original est 100    
>Le montant du pourboire est 15.0    
>Le montant de la TVQ est 9.975000000000001    
>Le montant du TPS est 5.0    
>Le montant final est 129.975    
  
Utilisez _round_ pour arrondir à deux chiffres.

>Le montant original est 100  
>Le montant du pourboire est 15.0  
>Le montant de la TVQ est 9.98  
>Le montant du TPS est 5.0  
>Le montant final est 129.97  

Voici un cas d'erreur d'arrondi (129,97 au lieu de 129.98)

### Question 2
Échangez le contenu de deux variables.  
Supposons que _x_ vaut 5 et que _y_ vaut 2  
>x = 5  
>y = 2  
> \# écrire votre code ci-dessus  
>  
> print("La nouvelle valeur de x est", x)  
> print("La nouvelle valeur de y est", y)  

Et vous devriez obtenir 

>La nouvelle valeur de x est 2  
>La nouvelle valeur de y est 5  

Pour réussir ceci, vous allez avoir besoin d'une variable intermédiaire. C'est similaire au problème de deux bouteilles, l'une contenant un liquide rouge et l'autre avec un liquide bleu et, à la fin, on veut que la premère bouteille contienne le liquide bleu et la deuxième bouteille le liquide rouge. Pour réussir le transfert, ça prend une 3eme bouteille (vide).

En python, il est facile de faire cette opération sans utiliser une variable temporaire (réponse en classe) mais c'est toujours bon de savoir résoudre cela. 

### Question 3
Saisir le rayon d'un cercle et calculer l'aire du cercle. Utilisez 3.1416 pour pi  
Aire d'un cercle $= \pi r^2$  

>Saisir le rayon: 2
>L'aire du cercle est 12.5664  



