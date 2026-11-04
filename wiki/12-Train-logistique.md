# Train logistique

`Prefabs/Vehicles/SubwayTrain/SubwayTrain_Cargo.et` : un wagon rempli de caisses de ravitaillement, avec un coffre.

## Le coffre

- Accessible depuis les portes du wagon (2000 kg, objets jusqu'à 1 m).
- Ouvert à toutes les factions.

## Le ravitaillement

Le wagon transporte du ravitaillement (*supplies*) dans ses caisses, jusqu'à 3000.

| Bouton | Où | Effet |
|---|---|---|
| **Charger / Décharger les ressources** | Aux portes | Comme un camion du jeu : échange avec les stocks à moins de 25 m |
| **Vider le wagon dans la base** | Tableau de commande | Verse le ravitaillement dans le stock de la base la plus proche (30 m) et revend les objets du coffre à l'arsenal |

Messages possibles : *Wagon vide*, *Aucune base à moins de 30 m*, *Stock de la base plein*.

> Comme pour les camions du jeu, on ne fait pas glisser le wagon dans un stock depuis l'inventaire : on passe par ces boutons.

## Différences avec le train de passagers

- 3 places assises au lieu de 8.
- Publicités et numéro (8804) propres.

---

← [Sécurité anti-collision](11-Securite-anti-collision.md) · [Accueil](../README.md) · [Multijoueur](13-Multijoueur.md) →
