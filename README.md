**Projet IN511** - Algorithme PAM
> - Massina AMMAD
> - Khadija BEN AYED
> - Noé DEMANGE
> - Romain VILLA

# Introduction
La classification par partitionnement est une méthode de classification utilisée pour classer les observations, au sein d'un ensemble de données, en plusieurs groupes en fonction de leur similitude. Les algorithmes demandent à l'utilisateur de spécifier le nombre de clusters à générer.
Pour ce faire, plusieurs algorithmes existent, notamment :
- La méthode des _k-means_ dans laquelle chaque cluster est représentée par le centre ou la moyenne des points de données appartenant au cluster. Cette méthode est cependant sensible au _outliers_ (valeurs aberrantes).
- La méthode des _k-médoïdes_ dans laquelle chaque cluster est représenté par l'un des objets (déjà existant) du cluster. Ainsi, PAM, basé sur la méthode des _k-médoïdes_, est un algorithme moins sensible au données "anormales".

L’algorithme PAM est une alternative à l’algorithme des K-means. En entr ́ee on a K un nombre de clusters qui seront retourn ́es par l’algorithme, et D un data set de N objets. En sortie, on obtient K clusters. L’id ́ee de l’algorithme est de construire les clusters autour d’objets repr ́esentatifs. Chaque cluster est associ ́e `a un objet qui le repr ́esente. Noter imm ́ediatement qu’un objet repr ́esentatif est un objet de l’ensemble D, alors que le barycentre dans les K-means n’est pas n ́ecessairement dans la population. L’algorithme PAM proc`ede comme suit
La classification des objets, en clusters, nécessite des méthodes pour mesurer la distance ou la (dis)similarité entre les objets. 

Pour chacune de ces méthodes, nous proposerons :
• l'idée de base
• l'algorithme de clustering et son implémentation dans le langage c pour k-means, le langage R pour PAM
Les packages R suivants seront utilisés pour calculer et visualiser le partitionnement en cluster :

## Algorithme PAM

### *il sert à quoi blabla*

## Complexité

## Perspectives 
L'algorithme CLARA (Clustering Large Applications), qui est une extension de PAM adaptée aux grands ensembles de données.

### *pour chaque itération*

## Comparaison des algorithmes PAM et des *k-means*
