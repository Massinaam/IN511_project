**Projet IN511** - Algorithme PAM
> - Massina AMMAD
> - Khadija BEN AYED
> - Noé DEMANGE
> - Romain VILLA

# Introduction
La classification par partitionnement est une méthode de classification utilisée pour classer les observations, au sein d'un ensemble de données, en plusieurs groupes en fonction de leurs similitudes.
Pour ce faire, plusieurs algorithmes existent, notamment :
- La méthode des _k-means_ dans laquelle chaque cluster est représentée par le centre ou la moyenne des points de données appartenant au cluster. 
- La méthode des _k-médoïdes_ dans laquelle chaque cluster est représenté par l'un des objets (déjà existant) du cluster. PAM est un algorithme basé sur cette méthode.

Pour chacune de ces méthodes, nous présenterons :
- l'idée de base
- l'algorithme de clustering et son implémentation
- la complexité de l'algorithme

Enfin nous comparerons les 2 méthodes.

Les algorithmes seront implémentés de la façon suivante :
- Langage C pour PAM ;
- Langage R pour _k-means_.


$\sum_{n=1}^{10} n^2$

# Algorithme PAM
## Algorithme et son implémentation en langage C
L'algorithme PAM est basé sur la recherche de k objets (médoïdes) représentatifs parmi les observations de l'ensemble de données. Le but est de trouver k objets représentatifs qui minimisent la somme des dissemblances des observations à leur objet représentatif le plus proche.
## Complexité de l'algorithme

# Algorithme _k-means_
## Algorithme et son implémentation en langage R
L'algorithme k-means est un algorithme qui se base sur les moyennes. Étant donnés des points et un entier k, le problème est de diviser les points en k groupes, souvent appelés clusters, de façon à minimiser une certaine fonction. On considère la distance d'un point à la moyenne des points de son cluster ; la fonction à minimiser est la somme des carrés de ces distances.

Il existe une heuristique classique pour ce problème, souvent appelée méthodes des k-moyennes, utilisée pour la plupart des applications. Le problème est aussi étudié comme un problème d'optimisation classique, avec par exemple des algorithmes d'approximation.

## Complexité de l'algorithme


# Comparaison des deux algorithmes
L’algorithme PAM est une alternative à l’algorithme des K-means. En entrée on a K un nombre de clusters qui seront retournés par l’algorithme, et D un data set de N objets. En sortie, on obtient K clusters. L’idée de l’algorithme est de construire les clusters autour d’objets représentatifs. Chaque cluster est associé à un objet qui le représente. Noter immédiatement qu’un objet représentatif est un objet de l’ensemble D, alors que le barycentre dans les K-means n’est pas nécessairement dans la population. L’algorithme PAM procède comme suit
La classification des objets, en clusters, nécessite des méthodes pour mesurer la distance ou la (dis)similarité entre les objets. 
_k-means_ Cette méthode est cependant sensible au _outliers_ (valeurs aberrantes). est un algorithme moins sensible au données "anormales".

# Perspectives 
Parmi les algorithmes de partitionnement, l'algorithme CLARA (Clustering Large Applications), qui est une extension de PAM adaptée aux grands ensembles de données. Par ailleurs, outre les méthodes de partitionnement, il existe des méthodes de clustering hiérarchique.


