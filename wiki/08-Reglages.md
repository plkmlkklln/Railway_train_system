# Réglages

[← Accueil](../README.md)

Tous les réglages se font dans les propriétés des entités posées sur votre carte, sans toucher au mod.

## Train — `MRD_TrainComponent`

Sur le wagon `SubwayTrain_Vehicle`.

| Champ | Défaut | Rôle |
|---|---|---|
| Nom de la spline des rails | *(vide)* | **Obligatoire** : nom de la spline suivie |
| Vitesse | 6 m/s | Vitesse de croisière |
| Accélération et freinage | 0,25 m/s² | Accélération et freinage normaux |
| Freinage d'urgence | 1,5 m/s² | Freinage de l'arrêt d'urgence |
| Attente au démarrage de la partie | 30 s | Délai avant le premier départ |
| Attente au bout de la voie | 10 s | Pause avant le demi-tour |
| Durée d'un arrêt demandé au bouton | 30 s | Bouton « Arrêter le train » |
| Distance du centre aux bogies | 6 m | Le train fait demi-tour à cette distance du bout |
| Hauteur au-dessus du terrain | 0,3 m | Hauteur du wagon sur la voie |
| Portes et roues animées | oui | Portes, roues, plafonniers et phares |
| Sans physique | oui | Le wagon est placé par le script, sans subir de forces |

## Gare — `TrainStation`

| Champ | Défaut | Rôle |
|---|---|---|
| Durée de l'arrêt | 30 s | Temps passé en gare |
| Distance maximale entre la gare et la voie | 40 m | Au-delà, la gare est ignorée |

## Passage à niveau — `MRD_LevelCrossingComponent`

| Champ | Défaut | Rôle |
|---|---|---|
| Distance du train | 70 m | Distance à laquelle la barrière se ferme |
| Angle ouvert | 85° | Angle de la barrière levée |
| Durée de la manœuvre | 6 s | Temps pour lever ou baisser la barrière |

## Aiguillage — `MRD_RailSwitchEntity`

Remplis automatiquement par le générateur ; à modifier seulement si vous posez un aiguillage à la main.

| Champ | Rôle |
|---|---|
| Nom de la spline de la voie principale | Voie sur laquelle est posé l'aiguillage |
| Nom de la spline de la voie déviée | Voie qui part de l'aiguillage |

Suite : [Dépannage →](09-Depannage.md)
