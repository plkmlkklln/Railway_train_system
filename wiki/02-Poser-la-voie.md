# Poser la voie

[← Accueil](../README.md)

## Étapes

1. Dans le World Editor, créer une **spline** (`SplineShapeEntity`) le long du tracé voulu.
2. **Lui donner un nom** dans ses propriétés, par exemple `Rails_01`.
   C'est indispensable : le train et les aiguillages retrouvent la voie par ce nom.
3. Glisser le générateur `Prefabs/WEGenerators/Railways/WG_Rail_01.et` **sur la spline**, pour qu'il en devienne l'enfant.
4. Les rails apparaissent et se regénèrent à chaque modification de la spline.

## Ce que pose le générateur

| Morceau | Quand |
|---|---|
| Rail droit 15 m | La spline est presque droite sur 15 m |
| Courbe 51,5 m (17,6°) | La spline suit cet arc |
| Rail pré-courbé 15 m (rayon 25, 50, 100, 200 ou 400 m, gauche ou droite) | Le générateur prend la courbe qui colle le mieux à la spline |
| Rail droit 7 m | Pour finir un tronçon ou dans les cas restants |
| Fin de voie avec butoir (7,3 m) | À chaque bout libre de la voie |
| Aiguillage (14,7 m) | Quand une autre voie part de celle-ci, voir [Aiguillages](06-Aiguillages.md) |

Les rails suivent la hauteur du terrain et reposent sur un talus de ballast.

## Conseils de tracé

- Gardez des virages d'au moins **25 m de rayon** : le wagon a ses bogies à 12 m l'un de l'autre.
- Une courbe régulière donne de meilleurs raccords qu'une suite de points irréguliers.
- Pour forcer une regénération, déplacez légèrement un point de la spline puis remettez-le en place.
- Le train fait demi-tour à 6 m de chaque bout de la voie, devant le butoir.

Suite : [Le train →](03-Le-train.md)
