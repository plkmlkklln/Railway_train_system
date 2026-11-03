# Les gares

[← Accueil](../README.md)

## Poser une gare

1. Poser `Prefabs/Structures/Infrastructure/Railways/HarborRail_01/Pack/TrainStation.et` **à côté de la voie**, à moins de 40 m.
2. C'est tout : le train s'arrête au point de la voie le plus proche de la gare.

La gare affiche un panneau d'arrêt de train. Vous pouvez construire votre propre quai autour.

## Comportement

- Le train s'arrête à chaque passage, dans les deux sens, pendant **30 secondes** par défaut.
- Il ralentit progressivement et s'arrête précisément au niveau de la gare.
- Les portes s'ouvrent pendant l'arrêt, puis se ferment 3 secondes avant le départ.
- Un joueur peut faire partir le train plus tôt avec le bouton **Signal de départ** du wagon.
- Une gare posée près d'un bout de voie fonctionne aussi : le train s'y arrête puis fait demi-tour.

## Réglages de la gare

| Champ | Défaut | Rôle |
|---|---|---|
| Durée de l'arrêt | 30 s | Temps passé en gare |
| Distance maximale entre la gare et la voie | 40 m | Au-delà, la gare est ignorée |

Suite : [Passages à niveau →](05-Passages-a-niveau.md)
