# Sac à dos

Votre sac à dos (`/sac`) stocke automatiquement toutes les ressources récoltées avec votre Multi-Outil, sans encombrer votre inventaire.

## Vendre le contenu de votre sac

Vous pouvez vendre directement depuis l'interface du sac à dos, ou utiliser les raccourcis en jeu :

| Commande     | Effet                                          |
| ------------ | ---------------------------------------------- |
| `/sell`      | Vend tout le contenu vendable de votre sac à dos |
| `/sell hand` | Vend uniquement l'objet que vous tenez en main   |

## Paliers de capacité

Le sac à dos possède **10 paliers** de capacité, achetables avec de la Money :

| Tier | Capacité   | Prix                     |
| ---- | ---------- | ------------------------ |
| 1    | 5 000      | 50 000                   |
| 2    | 10 000     | 250 000                  |
| 3    | 25 000     | 10 000 000               |
| 4    | 50 000     | 150 000 000              |
| 5    | 100 000    | 750 000 000              |
| 6    | 250 000    | 10 milliards             |
| 7    | 500 000    | 750 milliards            |
| 8    | 1 000 000  | 25 000 milliards         |
| 9    | 5 000 000  | 900 000 milliards        |
| 10   | 10 000 000 | 50 millions de milliards |

## Multiplicateur de vente

Un système de niveaux augmente le multiplicateur de vente appliqué à votre sac, jusqu'à environ **x3.5** au niveau maximum. Ce multiplicateur s'applique aussi bien à la vente automatique qu'aux commandes `/sell` et `/sell hand`.

## Duplication de vente

Un second système de niveaux augmente la chance de dupliquer le gain d'une vente, pour maximiser vos revenus passifs.

## Fonctionnalités automatiques

* **Auto-condense** — condense automatiquement le contenu de votre sac toutes les 2 minutes.
* **Auto-vente** — vend automatiquement le contenu de votre sac toutes les 2 minutes.

{% hint style="info" %}
Les commandes `/autocondense` et `/autovente` nécessitent le [grade](../grades/rangs-et-permissions.md) **Pionnier** minimum, indispensables pour jouer efficacement en semi-AFK.
{% endhint %}
