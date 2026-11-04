# Poser la voie

## Étapes

1. Dans le World Editor, créez une **spline** (`SplineShapeEntity`) le long du tracé.
2. **Donnez-lui un nom** dans ses propriétés, par exemple `Rails_01`.
   C'est indispensable : trains, gares, bornes et aiguillages retrouvent la voie par ce nom.
3. Glissez `Prefabs/WEGenerators/Railways/WG_Rail_01.et` **sur la spline**, pour qu'il en devienne l'enfant.
4. Les rails apparaissent, et se regénèrent à chaque modification de la spline.

## Ce que pose le générateur

| Morceau | Quand |
|---|---|
| Rail droit 15 m | Spline presque droite sur 15 m |
| Courbe 51,5 m (17,6°) | Spline qui suit cet arc |
| Rail pré-courbé 15 m (rayon 25, 50, 100, 200 ou 400 m, gauche/droite) | La courbe qui colle le mieux |
| Rail droit 7 m | Fin de tronçon, cas restants |
| Butoir (7,3 m) | À chaque bout libre de la voie |
| Aiguillage (14,7 m) | Quand une autre voie part de celle-ci ([Aiguillages](08-Aiguillages.md)) |

Les rails suivent le terrain et reposent sur un talus de ballast.

## Ponts

Posez `Prefabs/Railway/1_A_placer/RailBridgeZone.et` sur la voie, à l'endroit du pont, et tournez-le dans l'axe de la voie.
Dans sa zone (30 m de long, 10 m de large par défaut), la voie ne suit plus le terrain : elle passe en ligne droite d'une rive à l'autre, à la hauteur des deux bouts.

## Conseils

- Gardez des virages d'au moins **25 m de rayon** : les bogies sont à 13 m l'un de l'autre.
- Une courbe régulière donne de meilleurs raccords qu'une suite de points irréguliers.
- Pour forcer une regénération : déplacez un point de la spline puis remettez-le.
- Les trains s'arrêtent à 12 m du bout de la voie (centre du wagon), devant le butoir.

---

← [Où trouver les objets](02-Organisation-des-prefabs.md) · [Accueil](../README.md) · [Les trains](04-Les-trains.md) →
