# Sac à dos (Backpack)

Ton sac à dos (`/omnibackpack`, alias `/obp` ou `/sac`) stocke automatiquement toutes les ressources récoltées avec ton Multi-Outil, sans encombrer ton inventaire.

## Vendre le contenu de ton sac

Tu peux vendre directement depuis l'interface du sac à dos, ou utiliser les raccourcis en jeu :

| Commande | Effet |
|---|---|
| `/sell` | Ouvre l'interface de vente |
| `/sell all` | Vend tout le contenu vendable de ton sac à dos |
| `/sell hand` | Vend uniquement l'objet que tu tiens en main |

## Paliers de capacité

Le sac à dos possède **10 paliers** de capacité, achetables avec de la Money :

| Tier | Capacité | Prix |
|---|---|---|
| 1 | 5 000 | 50 000 |
| 2 | 10 000 | 250 000 |
| 3 | 25 000 | 10 000 000 |
| 4 | 50 000 | 150 000 000 |
| 5 | 100 000 | 750 000 000 |
| 6 | 250 000 | 10 milliards |
| 7 | 500 000 | 750 milliards |
| 8 | 1 000 000 | 25 000 milliards |
| 9 | 5 000 000 | 900 000 milliards |
| 10 | 10 000 000 | 50 millions de milliards |

## Multiplicateur de vente

Un système de niveaux (jusqu'à 25) augmente le multiplicateur de vente appliqué à ton sac, jusqu'à environ **x3.5** au niveau maximum. Ce multiplicateur s'applique aussi bien à la vente automatique qu'aux commandes `/sell`, `/sell all` et `/sell hand`.

## Duplication de vente

Un second système de niveaux (également jusqu'à 25) augmente la chance de dupliquer le gain d'une vente, pour maximiser tes revenus passifs.

## Fonctionnalités automatiques

* **Auto-pickup** — les ressources récoltées vont directement dans ton sac.
* **Auto-condense** — condense automatiquement le contenu de ton sac toutes les 2 minutes.
* **Auto-vente** — vend automatiquement le contenu de ton sac toutes les 2 minutes.

{% hint style="info" %}
Les commandes `/autocondense` et `/autovente` nécessitent le [grade](../rangs/rangs-et-permissions.md) **Pionnier** minimum, indispensables pour jouer efficacement en semi-AFK.
{% endhint %}
