# **BIENVENUE A VOUS QUI SOUHAITEZ MODIFIER VOTRE GCODE!**

<span style="color:red">Vous venez de générer votre Gcode mais vous souhaitez maintenant modifier les paramètres d'impression?
Pas de problème! Nous pouvons vous aider!</span>

*Notre programme vous permettera de diviser votre impression en plusieurs phases.*

Tout d'abord , vous sera demandé de rentrer le nombre de phases que vous souhaitez.

FONCTION 1 & 2:

Ensuite, vous deverez renseigner pour chacune d'elle:
1. La température initiale
2. La température finale
3. La vitesse initiale
4. La vitesse finale
5. Le pourcentage de couche qu'elle représente (leur somme doit valoir 100)

A l'aide de ces données, le programme modifiera pour chaque phase la température d’impression de manière variable entre la température initiale et la température finale
De la même façon, la vitesse d'impression sera modifiée de manière variable entre la vitesse initiale et la vitesse finale

FONCTION 4:

Il sera également possible pour vous de décaler la position de la pièce en X et en Y sur le lit
Pour cela, vous n'aurez qu'à renseigner en mm les longueur en X et en Y selon votre souhait.

FONCTION 5:

Enfin, en renseignant le facteur de déformation que vous souhaitez appliquer, le programme modifiera votre Gcode pour déformer la pièce afin de l’élargir dans une direction donnée de manière variable par rapport à l’axe z.
