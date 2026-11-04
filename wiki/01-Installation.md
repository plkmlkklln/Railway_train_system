# Installation

Railway Train System s'utilise comme **dépendance** de votre carte : votre carte s'appuie sur le mod, et les joueurs le téléchargent automatiquement avec elle.

## Ajouter le mod à votre carte

1. Abonnez-vous à **Railway Train System** sur le Workshop d'Arma Reforger (depuis le jeu ou depuis Workbench).
2. Ouvrez le projet de votre carte dans Workbench.
3. *Project → Settings*, section **Dependencies** : ajoutez **Railway_train_system** (identifiant `6AC6C5C085648081`).
4. **Redémarrez Workbench** pour charger les scripts du mod.

À la main, dans le fichier `addon.gproj` de votre carte (gardez vos autres dépendances) :

```
Dependencies {
 "58D0FB3206B6F859" "6AC6C5C085648081"
}
```

`58D0FB3206B6F859` est le jeu de base.

## Essayer tout de suite

Le mod contient un monde d'essai : `Worlds/MRD_TestTrain/MRD_TestTrain.ent`.
Ouvrez-le, lancez **Play**, montez dans le wagon et appuyez sur **Signal de départ**.

> Depuis cette version, les trains **attendent le signal de départ** au lancement de la partie au lieu de partir seuls. Voir [Les trains](04-Les-trains.md).

## Publier sa carte

À la publication sur le Workshop, la dépendance est enregistrée avec la carte : les joueurs reçoivent le mod automatiquement.

---

 · [Accueil](../README.md) · [Où trouver les objets](02-Organisation-des-prefabs.md) →
