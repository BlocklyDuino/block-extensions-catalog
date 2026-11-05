# block-extensions-catalog

Catalogue distant des packs de blocs **BlocklyDuino / electroBlockly**.

## Fichier

[`catalog.json`](./catalog.json) :

| Champ | Rôle |
|-------|------|
| `version` | Version du catalogue (comparée côté client pour mise à jour) |
| `schema` | Version du format |
| `extensions[]` | Entrées : `id`, `version`, `github`, `branch`, `packPath`, … |

URL canonique :

```
https://raw.githubusercontent.com/BlocklyDuino/block-extensions-catalog/main/catalog.json
```

## Ajouter une extension

1. Publier un dépôt pack (ex. [`block_servomotor`](https://github.com/BlocklyDuino/block_servomotor)).
2. Ajouter une entrée dans `catalog.json`.
3. Incrémenter `version` du catalogue.
