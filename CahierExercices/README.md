# Cahier de TP

## Génération du PDF

Pour générer le cahier de TP au format PDF, taper la commande suivante:
```
grunt generateCahierExercice
```

Il est possible de générer à la fois le cahier d'exercices et les slides au format PDF avec la commande `grunt pdf`

## Assets

Mettre des assets est possible mais le chemin pour les lier est peu pratique.

Voici un exemple d'image :

```markdown
![Node.js](../../../../../CahierExercices/ressources/logo-zenika.jpg)
```

Sauf en modifiant la librairie utiliser pour générer le PDF, il n'est pas
possible d'utiliser un chemin plus intuitif.
