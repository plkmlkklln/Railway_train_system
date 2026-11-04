# Dépannage

| Problème | Cause probable | Solution |
|---|---|---|
| Le train ne bouge pas au lancement | Il attend le signal de départ | Bouton **Signal de départ**, ou décocher *Attendre le signal de départ* |
| Journal : `MRD_Train : spline introuvable` | Spline sans nom, ou nom absent du train | Nommer la spline et recopier son nom |
| Borne : *Voie introuvable* | Nom de spline vide ou faux | Renseigner le nom sur la borne |
| Borne : *Voie occupée* | Un wagon à moins de 22 m | Déplacer le train ou la borne |
| Le train ne s'arrête pas en gare | Gare à plus de 40 m de la voie | Rapprocher la gare |
| Pas d'annonce en gare | Train trop loin ou annonce récente | Attendre 60 s ; vérifier la distance d'annonce |
| Les rails n'apparaissent pas | Générateur pas enfant de la spline | Glisser `WG_Rail_01` sur la spline |
| Rails décalés après une modification | Voie non regénérée | Déplacer un point de la spline puis le remettre |
| Pas d'aiguillage | Bout de la voie déviée à plus de 1,5 m, ou spline sans nom | Rapprocher le point, nommer les splines, regénérer la voie principale |
| *Aucun wagon à moins de 40 m* | Autre wagon trop loin ou sur une autre spline | Rapprocher les wagons sur la même voie |
| Le convoi ne repart pas au bout de la voie | Normal | Prendre les commandes dans le wagon de l'autre bout |
| Un train s'arrête en urgence sans raison visible | Un autre train devant, sur la même voie | Normal : sécurité anti-collision |
| Les changements n'apparaissent pas | Ancienne version gardée par Workbench | Redémarrer Workbench, reposer les trains |

## Où lire les messages du mod

Ils commencent par `MRD_` dans `Documents\My Games\ArmaReforgerWorkbench\logs\<date>\console.log`. Au lancement, par exemple :

```
MRD_Train : 4109 m, 3 gare(s), physique 1, dynamique 1
```

## Limites connues

- Les rails courbés n'ont pas de collision : on marche sur le talus et le terrain.
- Pas d'attelage à travers un aiguillage.
- Sur un long convoi, la queue peut dépasser du quai en gare.

---

← [Réglages](14-Reglages.md) · [Accueil](../README.md)
