# Installation

[← Accueil](../README.md)

Railway Train System s'utilise comme **dépendance** de votre projet : votre carte s'appuie sur le mod, et les joueurs le téléchargent automatiquement avec elle.

## Ajouter le mod en dépendance

1. Abonnez-vous au mod **Railway Train System** sur le Workshop d'Arma Reforger (depuis le jeu ou depuis Workbench). Workbench le télécharge alors avec ses autres addons.
2. Ouvrez le projet de votre carte dans Workbench.
3. Ouvrez *Project → Settings*, section **Dependencies**, et ajoutez **Railway_train_system**.
   Identifiant du projet : `6AC6C5C085648081`.
4. **Redémarrez Workbench** pour charger les scripts du mod.

Si vous préférez éditer le fichier `addon.gproj` de votre carte à la main, la ligne des dépendances ressemble à ceci (gardez vos autres dépendances) :

```
Dependencies {
 "58D0FB3206B6F859" "6AC6C5C085648081"
}
```

`58D0FB3206B6F859` est le jeu de base.

## Vérifier

Le mod contient un monde d'essai prêt à l'emploi : `Worlds/MRD_TestTrain/MRD_TestTrain.ent`.
Ouvrez-le et lancez **Play** : le train démarre après 30 secondes.

## Publier sa carte

À la publication de votre carte sur le Workshop, la dépendance est enregistrée avec elle : les joueurs reçoivent Railway Train System automatiquement.

Suite : [Poser la voie →](02-Poser-la-voie.md)
