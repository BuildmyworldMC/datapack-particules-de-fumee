# Datapack Particules de fumee - Edition Buildmyworld

Version supportée :

- 1.21.0 - 1.21.1

D'autres versions sont supportées disponible sur : https://buildmyworld.fr/resources

# Comment l'utiliser ?

Le datapack permet de placer des particules de fumée à la position du joueur ou d'en enlever à l'aide d'une commande simple.

Chaque commande commence par `/function` suivi du nom associé (qui apparaîtra dans la liste d'autocomplétion lorsque vous mettez un espace après le `/function`)
Placez vous au centre du block, les pieds au sommet du bloc et tapez la commande correspondante pour placer les particules de fumée à la bonne hauteur.
En cas d'erreur, vous pouvez supprimer un seul ou plusieurs "marker" (source des particules de fumée) à 2 blocs de distance maximum de votre position, à l'aide de commande

Les commandes sont les suivantes :

- `/function fvpdf:place_marker_block`

-> Place les particules de fumée au sommet d'un bloc ou demi-bloc.

- `/function fvpdf:place_marker_wall`

-> Place les particules de fumée au sommet d'un bloc de muret.

- `/function fvpdf:place_marker_flower_pot`

-> Place les particules de fumée au sommet d'un pot de fleur.

- `/function fvpdf:place_marker_composter`

-> Place les particules de fumée au fond d'un bloc de composteur. \
_NOTE : placez vous dans le composteur pour utiliser la commande._

- `/function fvpdf:kill_marker`

-> Supprime UN SEUL marker de particules de fumée, le plus proche, à une distance maximale de 2 blocs.

- `/function fvpdf:kill_aoe_marker`

-> Supprime TOUS les markers de particules de fumée à une distance maximale de 2 blocs.

---

Si les particules de fumée n'apparaissent plus, suite à un redémarrage par exemple, utiliser la fonction suivante pour relancer le datapack :

`/function fvpdf:init`
