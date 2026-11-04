# Sécurité anti-collision

Les trains d'une même voie **ne peuvent pas se traverser**.

- À chaque instant, le wagon de tête mesure l'écart avec le premier train devant lui (pour un convoi, depuis le bout du dernier wagon).
- Si cet écart devient inférieur à sa **distance de freinage d'urgence + 4 m**, il déclenche l'**arrêt d'urgence** : freinage fort, sonnerie, klaxon.
- En dernier recours, à moins de 50 cm, il s'arrête net.
- Un train arrêté juste derrière un autre ne peut pas repartir vers lui ; il peut repartir dans l'autre sens.

Après un arrêt d'urgence, le train attend le **signal de départ**.

> La mesure se fait en distance de parcours, un peu plus courte que les mètres réels : les trains s'arrêtent plutôt un peu trop tôt que trop tard.

La [borne d'appel](05-Borne-d-appel.md) refuse aussi de faire apparaître un train sur une voie occupée.

---

← [Attelage et convois](10-Attelage-et-convois.md) · [Accueil](../README.md) · [Train logistique](12-Train-logistique.md) →
