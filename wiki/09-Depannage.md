# Dépannage

[← Accueil](../README.md)

| Problème | Cause probable | Solution |
|---|---|---|
| Le train ne bouge pas | Spline sans nom, ou nom absent du train | Nommer la spline et recopier son nom dans **MRD_TrainComponent** |
| Journal : `MRD_Train : spline introuvable` | Même cause | Idem |
| Le train ne s'arrête pas en gare | Gare à plus de 40 m de la voie | Rapprocher la gare ou augmenter sa distance maximale |
| Les rails n'apparaissent pas | Générateur pas enfant de la spline | Glisser `WG_Rail_01` sur la spline |
| Rails décalés ou trous après une modification | Voie non regénérée | Déplacer un point de la spline puis le remettre |
| Pas d'aiguillage | Bout de la voie déviée à plus de 1,5 m de la voie principale, ou spline sans nom | Rapprocher le point, nommer les deux splines, regénérer la voie principale |
| Le train ignore l'aiguillage | Noms des splines absents de l'aiguillage | Regénérer la voie principale pour qu'il les renseigne |
| La barrière ne se ferme pas | Train à plus de 70 m | Rapprocher la barrière de la voie ou augmenter sa distance |
| Les changements n'apparaissent pas | Ancienne version gardée par Workbench | Redémarrer Workbench |

## Où lire les messages du mod

Les messages du mod commencent par `MRD_` dans le journal de Workbench :
`Documents\My Games\ArmaReforgerWorkbench\logs\<date>\console.log`

Au lancement, le train écrit par exemple :

```
MRD_Train : 4109 m, 3 gare(s), physique 1, dynamique 1
```

Ce message donne la longueur de la voie trouvée et le nombre de gares prises en compte.

## Limites connues

- Un seul wagon par train.
- Les rails courbés n'ont pas de collision ; on marche sur le talus et le terrain.
- Le dernier tronçon avant un aiguillage peut légèrement déborder sur lui.
- Pas encore de sons de train.

[← Accueil](../README.md)
