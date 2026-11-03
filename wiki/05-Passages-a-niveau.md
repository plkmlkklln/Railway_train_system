# Passages à niveau

[← Accueil](../README.md)

## Poser un passage à niveau

1. Poser `Prefabs/Structures/Infrastructure/Railways/HarborRail_01/Pack/LevelCrossing.et` au bord de la route, à côté de la voie.
2. Tournez-le pour que la barrière barre la route.
3. Rien à relier : il détecte lui-même les trains.

Pour fermer les deux côtés de la route, posez-en un de chaque côté de la voie.

## Comportement

- Quand un train arrive à moins de **70 m**, la barrière s'abaisse en 6 secondes.
- Les deux feux rouges clignotent en alternance, verres allumés, tant que la barrière n'est pas relevée.
- Une fois le train éloigné, la barrière se relève.
- En multijoueur, chaque joueur voit la barrière bouger au même moment.

## Réglages (`MRD_LevelCrossingComponent`)

| Champ | Défaut | Rôle |
|---|---|---|
| Distance du train | 70 m | Distance à laquelle la barrière se ferme |
| Angle ouvert | 85° | Angle de la barrière levée |
| Durée de la manœuvre | 6 s | Temps pour lever ou baisser la barrière |

Suite : [Aiguillages →](06-Aiguillages.md)
