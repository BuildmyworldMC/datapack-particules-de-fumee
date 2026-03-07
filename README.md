Le datapack permet de placer des particules de fumée à la position du joueur ou d'en enlever à l'aide d'une commande simple.

Chaque commande commence par "/function" suivi du nom associé (qui apparaîtra dans la liste d'autocomplétion lorsque vous mettez un espace après le "/function")
Placez vous au centre du block, les pieds au sommet du bloc et tapez la commande correspondante pour placer les particules de fumée à la bonne hauteur.
En cas d'erreur, vous pouvez supprimer un seul ou plusieurs "marker" (source des particules de fumée) à 2 blocs de distance maximum de votre position, à l'aide de commande

Les commandes sont les suivantes :

/function fvpdf:place_marker_block

-> place les particules de fumée au sommet d'un bloc ou demi-bloc.

/function fvpdf:place_marker_wall

-> place les particules de fumée au sommet d'un bloc de muret.

/function fvpdf:place_marker_flower_pot

-> place les particules de fumée au sommet d'un pot de fleur.

/function fvpdf:place_marker_composter

NOTE : placez vous dans le composteur pour utiliser la commande.

-> place les particules de fumée au fond d'un bloc de composteur.

/function fvpdf:kill_marker

-> supprime UN SEUL marker de particules de fumée, le plus proche, à une distance maximale de 2 blocs.

/function fvpdf:kill_aoe_marker

-> supprime TOUS les markers de particules de fumée à une distance maximale de 2 blocs.

------------------------------------------------------------------------------------------------------------

Si les particules de fumée n'apparaissent plus, suite à un redémarrage par exemple, utiliser la fonction suivante pour relancer le datapack :

/function fvpdf:init
