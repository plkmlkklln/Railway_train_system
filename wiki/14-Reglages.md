# Réglages

Tous les réglages se font dans les propriétés des objets posés, sans toucher au mod.

## Train — `MRD_TrainComponent`

| Champ | Défaut | Rôle |
|---|---|---|
| Nom de la spline des rails | *(vide)* | **Obligatoire** si le train est posé à la main |
| Vitesse | 6 m/s | Vitesse du mode Classique |
| Accélération et freinage | 0,25 m/s² | Freinage normal |
| Freinage d'urgence | 1,5 m/s² | Arrêt d'urgence et sécurité |
| Attendre le signal de départ | oui | Au lancement, attendre le bouton |
| Attente au démarrage | 60 s | Si la case précédente est décochée |
| Attente au bout de la voie | 10 s | Avant le demi-tour |
| Durée d'un arrêt demandé | 30 s | Bouton « Arrêter le train » |
| Arrêt avant le bout de la voie | 12 m | Centre du wagon ↔ bout |
| Hauteur au-dessus du terrain | 0,3 m | |
| Portes et roues animées | oui | Portes, roues, bogies, lumières |
| Sans physique | oui | Le script place le wagon |

## Gare — `TrainStation`

| Champ | Défaut |
|---|---|
| Durée de l'arrêt | 30 s |
| Distance maximale entre la gare et la voie | 40 m |

## Haut-parleur — `MRD_StationSpeakerComponent`

| Champ | Défaut |
|---|---|
| Distance d'annonce | 150 m |
| Distance minimale | 20 m |
| Délai entre deux annonces | 60 s |

## Borne d'appel — `MRD_TrainSpawnerComponent`

Voir [Borne d'appel](05-Borne-d-appel.md).

## Passage à niveau — `MRD_LevelCrossingComponent`

| Champ | Défaut |
|---|---|
| Distance du train | 70 m |
| Angle ouvert | 85° |
| Durée de la manœuvre | 6 s |

## Zone de pont — `RailBridgeZone`

| Champ | Défaut |
|---|---|
| Longueur du pont | 30 m |
| Largeur de la zone | 10 m |

## Aiguillage — `MRD_RailSwitchEntity`

Remplis automatiquement par le générateur : *Nom de la spline de la voie principale*, *Nom de la spline de la voie déviée*.

---

← [Multijoueur](13-Multijoueur.md) · [Accueil](../README.md) · [Dépannage](15-Depannage.md) →
