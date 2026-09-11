# Les îles

Le système d'îles de LostEra te permet de jouer seul ou en équipe, de progresser et de grimper dans le classement des îles.

## Créer ou rejoindre une île

```
/is create <nom>
```

Tu peux aussi rejoindre l'île d'un ami en équipe plutôt que de jouer en solo.

| Commande | Description |
|---|---|
| `/island` (ou `/is`, `/islands`) | Commande principale de gestion d'île |

## Caractéristiques de base

* **Taille par défaut** : 50 blocs de rayon
* **Taille maximale** : 200 blocs de rayon
* **Membres maximum de base** : 4 coéquipiers (améliorable, voir ci-dessous)
* **Coop maximum** : 0 par défaut
* **Warps d'île** : 3 maximum
* **Monde des îles** : `Island_World`

{% hint style="info" %}
Le Nether et l'End sont désactivés sur le monde des îles — toute ta progression se fait dans le monde principal.
{% endhint %}

## Améliorations d'île

Depuis le menu d'amélioration d'île, tu peux investir de la Money pour repousser plusieurs limites :

### Limite de Hoppers

| Niveau | Limite | Prix |
|---|---|---|
| 1 | 32 → 64 | 500M Money |
| 2 | 64 → 128 | 5B Money |
| 3 | 128 → 256 | 100B Money |
| 4 (max) | 256 | — |

### Limite de Membres

| Niveau | Limite | Prix |
|---|---|---|
| 1 | 4 → 5 | 5B Money |
| 2 (max) | 5 → 6 | 500B Money |

### Limite de Bordure

| Niveau | Limite | Prix |
|---|---|---|
| 1 | 101x101 → 131x131 | 100B Money |
| 2 | 131x131 → 161x161 | 250T Money |
| 3 | 161x161 → 191x191 | 500T Money |
| 4 (max) | 191x191 | — |

## Classement des îles (Island Top)

Le classement des îles repose sur un système de **trophées** : ton île en gagne en fonction de ton classement hebdomadaire dans les activités de farming, minage, pêche et gens (voir [Classements](../communaute/classements.md)).

{% hint style="warning" %}
Selon le nombre de membres sur ton île, tu es comparé dans l'un de ces **2 classements de trophées distincts** :

* **Solo** — îles à 1 seul membre
* **Team+** — îles à 2 membres ou plus
{% endhint %}

Chaque semaine, les 3 meilleures îles de chaque classement remportent des **LostCoins** :

| Position | Solo | Team+ |
|---|---|---|
| 🥇 1er | 1 500 LostCoins + Titre Trophées | 6 000 LostCoins + Titre Trophées |
| 🥈 2e | 1 250 LostCoins | 5 500 LostCoins |
| 🥉 3e | 1 000 LostCoins | 5 000 LostCoins |

## Limites de blocs et d'entités

Pour préserver les performances du serveur, certaines limites s'appliquent par île, par exemple :

* Hoppers : limite de base 32 (améliorable jusqu'à 256, voir ci-dessus)
* Wagonnets (minecarts) : 4 par défaut
