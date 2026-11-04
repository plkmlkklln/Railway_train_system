# Railway Train System — Wiki

Mod pour **Arma Reforger** : voies ferrées posées par spline, trains de métro sur lesquels on monte, gares avec quai et annonces, passages à niveau, aiguillages, attelage de wagons, borne d'appel et sécurité anti-collision. Tout fonctionne en multijoueur.

## Par où commencer

1. [Installer le mod](wiki/01-Installation.md) dans votre carte.
2. Repérer [où sont les objets](wiki/02-Organisation-des-prefabs.md) : **tout ce qui se pose est dans `Prefabs/Railway/1_A_placer`**.
3. [Poser une voie](wiki/03-Poser-la-voie.md) : une spline nommée + le générateur `WG_Rail_01`.
4. Poser une [gare](wiki/06-Les-gares.md) et une [borne d'appel](wiki/05-Borne-d-appel.md) à côté.
5. **Play** : appelez un train à la borne, montez, **Signal de départ**.

## Toutes les pages

| | Page | Contenu |
|---|---|---|
| **Mise en place** | [Installation](wiki/01-Installation.md) | Ajouter le mod à sa carte |
| | [Où trouver les objets](wiki/02-Organisation-des-prefabs.md) | Rangement des préfabs, quoi poser |
| | [Poser la voie](wiki/03-Poser-la-voie.md) | Spline, générateur, courbes, butoirs, ponts |
| | [Les trains](wiki/04-Les-trains.md) | Passagers et logistique, comportement |
| | [Borne d'appel](wiki/05-Borne-d-appel.md) | Faire venir un train en jeu |
| | [Les gares](wiki/06-Les-gares.md) | Quai, arrêts, annonce au haut-parleur |
| | [Passages à niveau](wiki/07-Passages-a-niveau.md) | Barrière et feux automatiques |
| | [Aiguillages](wiki/08-Aiguillages.md) | Embranchements et levier |
| **En jeu** | [Commandes en jeu](wiki/09-Commandes-en-jeu.md) | Boutons, tableau de commande, places |
| | [Attelage et convois](wiki/10-Attelage-et-convois.md) | Atteler, dételer, conduire un convoi |
| | [Sécurité anti-collision](wiki/11-Securite-anti-collision.md) | Arrêt d'urgence automatique |
| | [Train logistique](wiki/12-Train-logistique.md) | Coffre, ravitaillement, vider le wagon |
| **Technique** | [Multijoueur](wiki/13-Multijoueur.md) | Comment le train est partagé |
| | [Réglages](wiki/14-Reglages.md) | Tous les paramètres |
| | [Dépannage](wiki/15-Depannage.md) | Problèmes courants |

## Nouveautés

- **Borne d'appel** : faire apparaître un train au plus près, après vérification que la voie est libre.
- **Gare = quai** couvert, et **haut-parleur à poser** qui annonce l'arrivée des trains.
- **Attelage** de wagons en convoi, prise de commandes à chaque bout, bogies articulés dans les virages.
- **Sécurité anti-collision** : arrêt d'urgence automatique devant un autre train.
- **Train logistique** : coffre, ravitaillement, bouton « Vider le wagon dans la base ».
- Tableau de commande : 5 vitesses, klaxon, sens de marche, portes, arrêt d'urgence.
- Panneaux à **texte défilant**, **voyants de portes**, livrée bleue, logo et numéros de série.
- Départ sur **signal** au lancement de la partie.
- Préfabs **rangés** par usage.
