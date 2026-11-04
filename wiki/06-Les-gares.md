# Les gares

## Poser une gare

1. Posez `Prefabs/Railway/1_A_placer/TrainStation.et` **le long de la voie**, à moins de 40 m.
2. Tournez-la pour que le quai longe la voie.

La gare **est** le quai : un quai couvert, avec collisions. Le train s'arrête au point de la voie le plus proche de la gare.

## L'arrêt

- Le train s'arrête à chaque passage, dans les deux sens, **30 secondes** par défaut.
- Il ralentit progressivement et s'arrête au niveau du quai.
- Les portes s'ouvrent, puis se ferment 3 secondes avant le départ, avec une sonnerie.
- Un joueur peut faire partir le train plus tôt avec **Signal de départ**.

## Le haut-parleur (facultatif)

Posez `Prefabs/Railway/1_A_placer/StationSpeaker.et` où vous voulez : sur le quai, sur un poteau… ou pas du tout.

Comme le passage à niveau, **il détecte lui-même les trains** : quand un train roule vers lui à moins de **150 m**, il joue l'annonce — un carillon, puis une voix anglaise : *« Attention please. The train is now arriving at the platform… »*.

- Au plus une annonce par minute, pas d'annonce si le train est déjà à moins de 20 m.
- Tous les joueurs l'entendent au même moment.
- Le son est dans `Sounds/Station/Station_Annonce.wav` : remplacez ce fichier pour changer l'annonce.

| Réglage (`MRD_StationSpeakerComponent`) | Défaut |
|---|---|
| Distance d'annonce | 150 m |
| Distance minimale | 20 m |
| Délai entre deux annonces | 60 s |
| Événement sonore | `SOUND_STATION_ANNOUNCE` |

## Réglages (sur la gare)

| Champ | Défaut | Rôle |
|---|---|---|
| Durée de l'arrêt | 30 s | Temps passé en gare |
| Distance maximale entre la gare et la voie | 40 m | Au-delà, la gare est ignorée |

---

← [Borne d'appel](05-Borne-d-appel.md) · [Accueil](../README.md) · [Passages à niveau](07-Passages-a-niveau.md) →
