# Exos-GIF

Base d'animations d'exercices de musculation pour l'application YNSCOACHING.

- 813 animations (GIF et WebP), 360 × 360 px pour les ajouts récents
- Noms de fichiers en anglais, en minuscules et séparés par des tirets (`barbell-hip-thrust.gif`)
- Index complet dans [`exercices.json`](exercices.json)

## Index

Chaque entrée de `exercices.json` :

| Champ | Contenu |
|---|---|
| `fichier` | nom du fichier à la racine du dépôt |
| `nom_fr` | nom de l'exercice en français |
| `nom_en` | nom de l'exercice en anglais |
| `zone` | `abdominaux`, `bras`, `dos-trapezes`, `epaules`, `pectoraux`, `membres-inferieurs`, `mobilite`, `cardio`, `pliometrie`, `halterophilie`, `pieds` |
| `source` | `existant` ou `drive-animacoes` (lot ajouté le 23/09/2026) |
| `nom_pt` | nom d'origine en portugais, pour le lot `drive-animacoes` |

URL directe d'un fichier :

```
https://raw.githubusercontent.com/ynscoaching/Exos-GIF/main/<fichier>
```

## Droits

Une partie des animations suit le style Gym visual (gymvisual.com). Le lot `drive-animacoes` vient d'un pack revendu, sans licence jointe. Avant d'afficher ces fichiers à des clients payants, vérifier qu'une licence couvre cet usage.
