# Les trains

Deux trains sont fournis :

| Train | Préfab | Particularités |
|---|---|---|
| Passagers | `Prefabs/Vehicles/SubwayTrain/SubwayTrain_Vehicle.et` | 8 places assises, numéro 8805 |
| Logistique | `Prefabs/Vehicles/SubwayTrain/SubwayTrain_Cargo.et` | caisses de ravitaillement, coffre, 3 places, numéro 8804 ([page dédiée](12-Train-logistique.md)) |

## Poser un train

**Méthode simple : la [borne d'appel](05-Borne-d-appel.md).** Le train apparaît en jeu, déjà relié à la voie.

**À la main dans le World Editor :**
1. Posez le préfab **sur la voie**.
2. Dans le composant **MRD_TrainComponent**, renseignez **Nom de la spline des rails** (par exemple `Rails_01`).

Au lancement, le train se cale tout seul sur la voie, au point le plus proche.

## Au lancement de la partie

Par défaut, le train **attend le signal de départ**, portes ouvertes : il ne part pas seul.
Pour qu'il parte automatiquement après un délai, décochez **Attendre le signal de départ** et réglez **Attente au démarrage** (voir [Réglages](14-Reglages.md)).

## En route

- Il accélère et freine en douceur ; 5 vitesses au choix depuis le tableau de commande.
- Il s'arrête à chaque [gare](06-Les-gares.md), dans les deux sens.
- Au bout de la voie, il attend 10 secondes puis repart dans l'autre sens (un [convoi](10-Attelage-et-convois.md), lui, attend qu'on prenne les commandes à l'autre bout).
- Aux [aiguillages](08-Aiguillages.md), il prend la voie choisie au levier.
- Il ne peut ni dérailler ni exploser, et s'arrête tout seul devant un autre train ([sécurité](11-Securite-anti-collision.md)).

## À bord et autour

- On marche dans le wagon et on reste emporté pendant le trajet.
- Portes automatiques, sonnerie avant la fermeture, vitres cassables.
- Plafonniers la nuit, phares aux deux bouts, vapeur et étincelles des freins.
- **Panneaux à texte défilant** orange au-dessus des portes de bout et à l'intérieur.
- **Voyants de portes** orange aux quatre coins des flancs : allumés tant qu'une porte est ouverte, comme sur un vrai métro.
- Bogies séparés qui pivotent dans les virages.
- Livrée : faces avant et arrière bleues, logo CCA et numéro de série sur chaque face.
- Sons : portes, sonnerie, départ, roulement, freinage, klaxon.

---

← [Poser la voie](03-Poser-la-voie.md) · [Accueil](../README.md) · [Borne d'appel](05-Borne-d-appel.md) →
