**Projet IN511** - Algorithme PAM
> - Massina AMMAD
> - Khadija BEN AYED
> - Noé DEMANGE
> - Romain VILLA

# Introduction
La classification par partitionnement est une méthode de classification utilisée pour classer les observations, au sein d'un ensemble de données, en plusieurs groupes en fonction de leurs similitudes. Les algorithmes demandent à l'utilisateur de spécifier le nombre de clusters à générer.
Pour ce faire, plusieurs algorithmes existent, notamment :
- La méthode des _k-means_ dans laquelle chaque cluster est représentée par le centre ou la moyenne des points de données appartenant au cluster. 
- La méthode des _k-médoïdes_ dans laquelle chaque cluster est représenté par l'un des objets (déjà existant) du cluster. PAM est un algorithme basé sur cette méthode.

Pour chacune de ces méthodes, nous proposerons :
- l'idée de base
- l'algorithme de clustering et son implémentation
- la complexité de l'algorithme
Enfin nous comparerons les 2 méthodes.
Les algorithmes seront implémentés de la façon suivante :
      Langage c pour _k-means_ ;
      Langage R pour PAM.
# _k-means_
L'algorithme k-means est un algorithme qui se base sur les moyennes. Étant donnés des points et un entier k, le problème est de diviser les points en k groupes, souvent appelés clusters, de façon à minimiser une certaine fonction. On considère la distance d'un point à la moyenne des points de son cluster ; la fonction à minimiser est la somme des carrés de ces distances.



Il existe une heuristique classique pour ce problème, souvent appelée méthodes des k-moyennes, utilisée pour la plupart des applications. Le problème est aussi étudié comme un problème d'optimisation classique, avec par exemple des algorithmes d'approximation.


La classification des observations en groupes nécessite certaines méthodes de calcul de la distance ou de la (dis)similarité entre chaque paire d'observations. Le résultat de ce calcul est connu sous le nom de matrice de dissimilarité ou de distance.

## Algorithme PAM

### *il sert à quoi blabla*

## Complexité

## Perspectives 
L'algorithme CLARA (Clustering Large Applications), qui est une extension de PAM adaptée aux grands ensembles de données.

### *pour chaque itération*

## Comparaison des algorithmes PAM et des *k-means*
% L’algorithme PAM est une alternative à l’algorithme des K-means. En entrée on a K un nombre de clusters qui seront retournés par l’algorithme, et D un data set de N objets. En sortie, on obtient K clusters. L’idée de l’algorithme est de construire les clusters autour d’objets représentatifs. Chaque cluster est associé à un objet qui le représente. Noter immédiatement qu’un objet représentatif est un objet de l’ensemble D, alors que le barycentre dans les K-means n’est pas nécessairement dans la population. L’algorithme PAM procède comme suit
La classification des objets, en clusters, nécessite des méthodes pour mesurer la distance ou la (dis)similarité entre les objets. 

_k-means_ Cette méthode est cependant sensible au _outliers_ (valeurs aberrantes).
 est un algorithme moins sensible au données "anormales".
