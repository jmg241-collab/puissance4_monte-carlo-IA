# puissance4_monte-carlo-IA
Ce projet consiste à implémenter une intelligence artificielle capable de jouer au jeu puissance 4 en utilisant des simulations de Monte carlo.
Pour chaquue coup possible, un nombre fixé de parties aléatoires est simulé afin d'estimer la probabilité de victoire. Le coup sélectionné est celui présentant le meilleur ratio de victoires.
Ce projet a été realisé dans le cadre d'un stage de Licence 3 de mathématiques.

Représentation du plateau :
O : case vide
1 : pion rouge
2 : pion Jaune

Méthode :
L'algorithme évalue chaque coup possible en :
1. Simulant plusieurs parties aléatoires à partir de ce coup
2. calculant le taux de victoire obtenu
3.  sélectionne le coup avec le meilleur score
Il s'agit d'une approche par simulation probabiliste inspirée des méthodes de Monté Carlo.

Langage : Python (Numpy,Time,Random)

Resultats :
Le notebook contient un test ou l'algorithme affronte l'aléatoire. Les resultats de la simulation s'affiche directement après l'execution du fichier. 
(en mettant le nombre de simulation a un nombre un peu plus élevé l'algorithme a meme réussit a battre une de mes camarades, mais bon le temps de réponse est plus long cependant)
Et enfin, ce projet a été effectué avec deux autres camarades ce qui peut expliquer parfois le manque d'uniformité dans l'écriture de certaines fonctions au début.

