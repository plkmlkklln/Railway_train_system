# Borne d'appel

La borne fait **apparaître un train en jeu**, directement sur la voie, au plus près d'elle.

## Poser une borne

1. Posez `Prefabs/Railway/1_A_placer/TrainSpawner.et` près de la voie.
2. Dans le composant **MRD_TrainSpawnerComponent**, renseignez **Nom de la spline de la voie desservie**.
3. La liste **Trains proposés** contient déjà *Passagers* et *Logistique*. Ajoutez-en autant que vous voulez : un nom et un préfab chacun.

## En jeu

Devant la borne :

| Bouton | Effet |
|---|---|
| **Train choisi : …** | Passe au train suivant de la liste |
| **Faire venir : …** | Fait apparaître le train choisi |

## Où apparaît le train

- Sur le **point de la voie le plus proche de la borne**, dans le sens de la voie.
- Si la borne est près d'un bout de voie, le train est décalé vers l'intérieur jusqu'à la première place valide (12 m du bout, mesuré au centre du wagon).
- Le train apparaît relié à sa voie et attend le signal de départ.

## Vérification avant l'apparition

Le bouton est grisé, avec un message :

| Message | Raison |
|---|---|
| *Voie occupée* | Un wagon est à moins de 22 m du point d'apparition |
| *Voie introuvable* | Le nom de la spline est vide ou faux |
| *Aucun train dans la liste* | La liste des trains est vide |

## Réglages

| Champ | Défaut | Rôle |
|---|---|---|
| Nom de la spline de la voie desservie | *(vide)* | **Obligatoire** |
| Trains proposés | Passagers, Logistique | Nom affiché + préfab |
| Distance minimale au bout de la voie | 12 m | Place du centre du train près d'un bout |
| Rayon contrôlé | 22 m | Aucun wagon ne doit s'y trouver |
| Hauteur au-dessus du terrain | 0,3 m | Hauteur d'apparition |

---

← [Les trains](04-Les-trains.md) · [Accueil](../README.md) · [Les gares](06-Les-gares.md) →
