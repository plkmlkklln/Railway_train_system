# Le train

[← Accueil](../README.md)

## Poser le train

1. Poser `Prefabs/Vehicles/SubwayTrain/SubwayTrain_Vehicle.et` **sur la voie**.
2. Dans ses composants, ouvrir **MRD_TrainComponent**.
3. Renseigner **Nom de la spline des rails** avec le nom de votre spline, par exemple `Rails_01`.

Au lancement de la partie, le train se cale tout seul sur la voie au point le plus proche, attend 30 secondes, puis démarre.

## Comportement

- Il roule à 6 m/s, accélère et freine en douceur.
- Il s'arrête à chaque [gare](04-Les-gares.md), dans les deux sens.
- Au bout de la voie, il attend 10 secondes puis repart dans l'autre sens.
- Aux [aiguillages](06-Aiguillages.md), il prend la voie indiquée par le levier.
- Il ne subit aucune force physique : il est placé par le script et ne peut ni dérailler ni exploser.

## À bord

- On marche dans le wagon et on reste emporté pendant le trajet.
- Les portes s'ouvrent en gare et se ferment 3 secondes avant le départ.
- 8 places assises.
- Les vitres se cassent.
- Les plafonniers s'allument la nuit ; les phares restent allumés aux deux bouts.

Les boutons de contrôle sont décrits dans [Commandes en jeu](07-Commandes-en-jeu.md), et tous les paramètres dans [Réglages](08-Reglages.md).

Suite : [Les gares →](04-Les-gares.md)
