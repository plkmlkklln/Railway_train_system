# Multijoueur

Tout fonctionne en multijoueur, sans réglage.

## Comment c'est fait

- Le **serveur** décide : départs, arrêts, gares, aiguillages, attelages, sécurité.
- Il partage avec chaque joueur la **distance parcourue sur la voie** et la **vitesse** de chaque train, quatre fois par seconde, ainsi que la composition des convois.
- Chaque machine **recalcule elle-même** la position exacte du wagon sur la voie : le train roule sans saccade, même avec de la latence.
- Les wagons attelés sont placés à partir du wagon de tête, à écart fixe, sur toutes les machines : ils ne se décalent jamais l'un de l'autre.
- Portes, voyants, sons, barrières et annonces se déclenchent au même moment pour tous.

Contrairement aux véhicules du jeu (calculés par la machine du conducteur), les trains n'ont pas de conducteur : c'est toujours le serveur qui décide de leur position.

## Tester à plusieurs dans Workbench

Lancez **Play** avec un deuxième client (Peer Tool), puis vérifiez que les deux joueurs voient le train rouler, les portes s'ouvrir et les convois rester attachés.

---

← [Train logistique](12-Train-logistique.md) · [Accueil](../README.md) · [Réglages](14-Reglages.md) →
