# Les gares

## Poser une gare

1. Posez `Prefabs/Railway/1_A_placer/TrainStation.et` **le long de la voie**, à moins de 40 m.
2. Tournez-la pour que le quai longe la voie.

La gare **est** le quai : un quai couvert (avec collisions) et un haut-parleur sous le toit. Le train s'arrête au point de la voie le plus proche de la gare.

## L'arrêt

- Le train s'arrête à chaque passage, dans les deux sens, **30 secondes** par défaut.
- Il ralentit progressivement et s'arrête au niveau du quai.
- Les portes s'ouvrent, puis se ferment 3 secondes avant le départ, avec une sonnerie.
- Un joueur peut faire partir le train plus tôt avec **Signal de départ**.

## L'annonce au haut-parleur

Quand un train **roule vers la gare à moins de 150 m**, le haut-parleur joue l'annonce :
un carillon, puis une voix anglaise : *« Attention please. The train is now arriving at the platform… »*.

- Au plus une annonce par minute.
- Tous les joueurs l'entendent au même moment.
- Le son est dans `Sounds/Station/Station_Annonce.wav` : remplacez ce fichier pour changer l'annonce.

## Réglages (sur la gare)

| Champ | Défaut | Rôle |
|---|---|---|
| Durée de l'arrêt | 30 s | Temps passé en gare |
| Distance maximale entre la gare et la voie | 40 m | Au-delà, la gare est ignorée |
| Distance d'annonce | 150 m | 0 : pas d'annonce |
| Délai entre deux annonces | 60 s | |

---

← [Borne d'appel](05-Borne-d-appel.md) · [Accueil](../README.md) · [Passages à niveau](07-Passages-a-niveau.md) →
