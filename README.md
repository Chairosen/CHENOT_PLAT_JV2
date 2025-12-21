# CHENOT_PLAT_JV2

## Le principe et l'expérience attendue 
Il est possible dans le jeu de **récupérer des pièces** qui permettent d'augmenter son **energie** en fonction du nombre de pièces obtenues. Ces pièces sont aussi utilisées pour **ouvrir des portes**.L'énergie augmente si le joueur bouge, autrement elle diminue. Le joueur doit **toujours être en mouvement**. Il peu utiliser son énergie pour **dasher**, en se transformant en sphère allongée (pour donner l'impression de vitesse) ce qui lui permet de passer sous des éléments, et pour **inverser la gravité** et ainsi marcher au plafond. Il ne peut changer la gravité que étant au sol mais peut dasher en l'air.

## Les touches
- **E** permet d'interagir avec les éléments du jeu.
- **Shift**/**Maj** permet de dasher.
- **Clique droit** de la souris permet d'inverser la gravité.
- **Z** permet d'avancer.
- **S** permet de reculer.
- **Q** permet d'aller à gauche.
- **D** permet d'aller droite.
- **Espace** permet de sauter.

## Les soucis rencontrés
- Dans la fonction Death, dans l'event graph de BP_ThirdPersonCharacter, la première condition censée vérifier si le niveau actuel correspond au tuto est laisée sur true, car avec les nodes que j'avais utilisés, Unreal crashait systématiquement. J'ai laissé en dessous, non relié, si tu veux jeter un coup d'oeuil.
- Il est aussi possible que tu n'arrive pas à passer sous le mur après la première porte. Je ne sais pas pourquoi ça m'a fait cette blague, mais uniquement sur mon ordinateur à la maison. Sur tous les ordinateurs de l'ESMA ça fonctionne mais bon.