# Aiguillages

[← Accueil](../README.md)

Un aiguillage relie une voie principale et une voie déviée. Il est posé automatiquement par le générateur de rails.

## Créer un embranchement

1. La voie principale existe déjà, avec une spline **nommée** (par exemple `Rails_01`) et son générateur.
2. Créez une **deuxième spline nommée** (par exemple `Rails_02`).
3. Posez son **premier ou son dernier point sur la voie principale**, à 1,5 m près, mais pas au bout de celle-ci.
4. Glissez-lui aussi le générateur `WG_Rail_01`.
5. Regénérez **d'abord la voie principale** (déplacez un de ses points puis remettez-le), puis la voie déviée.

Le générateur de la voie principale pose alors l'aiguillage (`RailSwitch_L` ou `RailSwitch_R` selon le côté de l'embranchement) et le relie aux deux splines. Il ne pose pas de rails sur les 14,7 m de l'aiguillage ; la voie déviée laisse aussi cette longueur libre.

## Bien tracer la voie déviée

L'aiguillage s'écarte d'environ 3 m sur ses 14,5 premiers mètres. Faites partir la voie déviée de la jonction en suivant à peu près cette courbe, sinon ses rails ne se raccordent pas bien au bout de l'aiguillage.

## Le levier

- Une action **Aiguillage** sur le levier bascule entre la voie principale et la voie déviée.
- Le drapeau tourne d'un quart de tour quand la voie déviée est choisie.
- Le choix est partagé entre tous les joueurs.

## Le train et l'aiguillage

- **En arrivant par la pointe** (le côté où les deux voies se séparent), le train prend la voie choisie au levier, y compris en marche arrière après un demi-tour.
- **En arrivant par l'autre côté**, il rejoint toujours la voie principale.

Suite : [Commandes en jeu →](07-Commandes-en-jeu.md)
