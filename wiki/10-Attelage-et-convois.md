# Attelage et convois

On peut atteler autant de wagons qu'on veut pour former un convoi.

## Atteler

1. Deux wagons sur **la même voie**, à moins de **40 m**, **à l'arrêt**.
2. Allez en bas d'un coin du wagon, du côté de l'autre wagon : bouton **Atteler le wagon**.
3. L'autre wagon (ou tout son convoi) avance au pas jusqu'à toucher les attelages, puis un coup de klaxon confirme l'attelage.

Messages possibles : *Aucun wagon à moins de 40 m de ce côté*, *Le wagon doit être à l'arrêt*, *L'autre wagon doit être à l'arrêt*.

## Dételer

Même bouton, du côté attelé : **Dételer le wagon** (convoi à l'arrêt). Les deux parties deviennent deux convois séparés.

## Conduire un convoi

- Un seul wagon conduit : le **wagon de tête**. Les autres suivent la voie à écart fixe.
- Au tableau, le bouton du sens de marche devient **Prendre les commandes du convoi**.
  Il ne marche que dans un wagon **à un bout** du convoi : le convoi roulera **vers ce bout**.
- Les boutons des wagons suiveurs (départ, arrêt, urgence, vitesse) commandent le wagon de tête.
- Au bout de la voie, le convoi **ne fait pas demi-tour seul** : il attend, portes ouvertes.
  Descendez, allez dans le wagon de l'autre bout et prenez les commandes pour repartir.

## Dans les virages

Chaque wagon suit les rails avec ses propres bogies : les caisses pivotent l'une par rapport à l'autre, comme un vrai train, et l'écart reste constant.

## Limites

- Les wagons doivent être sur la même spline (pas d'attelage à travers un aiguillage).
- Le convoi entier doit tenir sur la voie, marges de fin comprises.
- Les gares s'arrêtent sur la position du wagon de tête : sur un long convoi, la queue peut dépasser du quai.
- 64 wagons au plus par convoi.

---

← [Commandes en jeu](09-Commandes-en-jeu.md) · [Accueil](../README.md) · [Sécurité anti-collision](11-Securite-anti-collision.md) →
