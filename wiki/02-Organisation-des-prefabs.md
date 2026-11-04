# Où trouver les objets

Tous les objets du mod sont rangés par usage. **Vous n'avez besoin que du dossier `1_A_placer`, du générateur de voie et des trains.**

```
Prefabs/
  Railway/
    1_A_placer/                  ← à poser vous-même dans le monde
      TrainStation.et              gare : quai couvert + haut-parleur
      TrainSpawner.et              borne d'appel des trains
      LevelCrossing.et             passage à niveau complet
      RailEnd.et                   butoir (déjà posé automatiquement aux bouts)
      RailBridgeZone.et            zone de pont
    2_Poses_par_le_generateur/   ← posés automatiquement par WG_Rail_01 : ne pas poser à la main
      RailBend_25…400_L/R          rails pré-courbés
      RailCurve_L/R                courbes
      RailSwitch_L/R               aiguillages
    3_Pieces_internes/           ← morceaux des objets ci-dessus : ne pas poser seuls
      LevelCrossing_Arm, _ArmLamps, _Lamp, _LensL/R
      RailSwitchFlag_L/R
    4_Modeles_de_voie/           ← modèles de rails utilisés par le générateur
  WEGenerators/Railways/
    WG_Rail_01.et                ← générateur de voie, à glisser sur une spline
  Vehicles/SubwayTrain/
    SubwayTrain_Vehicle.et       ← train de passagers
    SubwayTrain_Cargo.et         ← train logistique
```

## Que poser, et où

| Je veux… | J'utilise | Page |
|---|---|---|
| Une voie ferrée | une spline nommée + `WG_Rail_01` | [Poser la voie](03-Poser-la-voie.md) |
| Un train | `SubwayTrain_Vehicle` ou `SubwayTrain_Cargo`, ou une borne d'appel | [Les trains](04-Les-trains.md) |
| Faire venir un train en jeu | `TrainSpawner` | [Borne d'appel](05-Borne-d-appel.md) |
| Une gare | `TrainStation` | [Les gares](06-Les-gares.md) |
| Une barrière sur une route | `LevelCrossing` | [Passages à niveau](07-Passages-a-niveau.md) |
| Un embranchement | une deuxième spline nommée | [Aiguillages](08-Aiguillages.md) |
| Un pont | `RailBridgeZone` | [Poser la voie](03-Poser-la-voie.md) |

---

← [Installation](01-Installation.md) · [Accueil](../README.md) · [Poser la voie](03-Poser-la-voie.md) →
