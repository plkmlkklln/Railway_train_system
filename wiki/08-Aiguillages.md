# Aiguillages

Un aiguillage relie une voie principale et une voie déviée. **Le générateur le pose tout seul.**

## Créer un embranchement

1. La voie principale existe, avec une spline **nommée** (`Rails_01`) et son générateur.
2. Créez une **deuxième spline nommée** (`Rails_02`).
3. Posez son **premier ou son dernier point sur la voie principale**, à 1,5 m près, mais pas au bout de celle-ci.
4. Glissez-lui aussi le générateur `WG_Rail_01`.
5. Regénérez **d'abord la voie principale** (déplacez un point puis remettez-le), puis la voie déviée.

Le générateur pose `RailSwitch_L` ou `RailSwitch_R` et le relie aux deux splines. Il laisse les 14,7 m de l'aiguillage libres de rails.

> Tracez la voie déviée en suivant à peu près la courbe de l'aiguillage : il s'écarte d'environ 3 m sur ses 14,5 premiers mètres.

## Le levier

- Action **Aiguillage** sur le levier : bascule entre voie principale et voie déviée.
- Le drapeau tourne d'un quart de tour sur la voie déviée.
- Le choix est partagé entre tous les joueurs.

## Le train et l'aiguillage

- **Par la pointe** (le côté où les voies se séparent) : le train prend la voie choisie au levier.
- **Par l'autre côté** : il rejoint toujours la voie principale.
- L'[attelage](10-Attelage-et-convois.md) ne se fait qu'entre wagons d'une même voie.

---

← [Passages à niveau](07-Passages-a-niveau.md) · [Accueil](../README.md) · [Commandes en jeu](09-Commandes-en-jeu.md) →
