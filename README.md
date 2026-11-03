# Railway Train System — Wiki

Documentation du mod **Railway Train System** pour Arma Reforger : voies ferrées posées par spline, train de métro automatique sur lequel on peut monter, gares, passages à niveau, aiguillages et butoirs de fin de voie.

Ce wiki explique comment ajouter le mod en dépendance à votre projet de carte, puis comment le mettre en place et le régler.

## Pages

| Page | Contenu |
|---|---|
| [Installation](wiki/01-Installation.md) | Ajouter le mod en dépendance à sa carte |
| [Poser la voie](wiki/02-Poser-la-voie.md) | Spline, générateur de rails, courbes, butoirs |
| [Le train](wiki/03-Le-train.md) | Poser le train et le relier à la voie |
| [Les gares](wiki/04-Les-gares.md) | Arrêts automatiques |
| [Passages à niveau](wiki/05-Passages-a-niveau.md) | Barrière et feux automatiques |
| [Aiguillages](wiki/06-Aiguillages.md) | Embranchements et levier |
| [Commandes en jeu](wiki/07-Commandes-en-jeu.md) | Boutons du wagon, places, levier |
| [Réglages](wiki/08-Reglages.md) | Tous les paramètres et leurs valeurs par défaut |
| [Dépannage](wiki/09-Depannage.md) | Problèmes courants et solutions |

## En bref

1. Ajouter **Railway Train System** aux dépendances de votre projet de carte.
2. Tracer une spline, **lui donner un nom**, y glisser le générateur `WG_Rail_01`.
3. Poser le wagon sur la voie et recopier le nom de la spline dans son composant `MRD_TrainComponent`.
4. Poser des gares et des passages à niveau le long de la voie.
5. Lancer **Play**.

## Fonctionnalités

**Voie**
- Rails générés le long d'une spline, qui suivent le terrain.
- Choix automatique du morceau : droit de 15 m ou de 7 m, courbe de 51,5 m, ou rail pré-courbé de 25 à 400 m de rayon.
- Butoir posé automatiquement à chaque bout de voie.
- Aiguillage posé automatiquement quand une voie part d'une autre.

**Train**
- On marche à bord et on reste emporté pendant le trajet.
- Conduite automatique : ralentit et s'arrête en gare, fait demi-tour au bout de la voie.
- Portes automatiques, roues animées, vitres cassables, places assises.
- Plafonniers la nuit, phares, vapeur à l'arrivée en gare.
- Boutons dans le wagon : signal de départ, arrêt demandé, arrêt d'urgence.

**Équipements**
- Passage à niveau dont la barrière se ferme à l'approche du train.
- Aiguillage à levier pour choisir la voie.
