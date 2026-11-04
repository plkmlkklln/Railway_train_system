# Passages à niveau

## Poser un passage à niveau

1. Posez `Prefabs/Railway/1_A_placer/LevelCrossing.et` au bord de la route, à côté de la voie.
2. Tournez-le pour que la barrière barre la route.
3. Rien à relier : il détecte lui-même les trains.

Pour fermer les deux côtés de la route, posez-en un de chaque côté de la voie.

## Comportement

- Un train à moins de **70 m** : la barrière s'abaisse en 6 secondes, avec une sonnerie.
- Les deux feux rouges clignotent en alternance tant que la barrière n'est pas relevée.
- Le train passé, la barrière se relève.

## Réglages (`MRD_LevelCrossingComponent`)

| Champ | Défaut | Rôle |
|---|---|---|
| Distance du train | 70 m | Distance de fermeture |
| Angle ouvert | 85° | Barrière levée |
| Durée de la manœuvre | 6 s | Lever ou baisser |

---

← [Les gares](06-Les-gares.md) · [Accueil](../README.md) · [Aiguillages](08-Aiguillages.md) →
