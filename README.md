# Activité balance — GitHub Pages

Activité interactive autonome pour travailler les équations avec une balance.

## Contenu

- `index.html` : l'activité complète, prête à être publiée.
- `.nojekyll` : fichier technique pour éviter que GitHub Pages modifie le rendu.

## Déploiement rapide

1. Créer un nouveau dépôt GitHub, par exemple `activite-balance`.
2. Envoyer les fichiers `index.html` et `.nojekyll` à la racine du dépôt.
3. Aller dans `Settings` > `Pages`.
4. Dans `Build and deployment`, choisir `Deploy from a branch`.
5. Sélectionner `main` puis `/root`, puis enregistrer.
6. Attendre 1 à 3 minutes.
7. Le lien sera de la forme :

```text
https://TON_PSEUDO.github.io/activite-balance/
```

## Intégration dans l'ENT

Dans le classeur pédagogique, ajouter une ressource de type lien ou page web, puis coller l'URL GitHub Pages obtenue.

Si l'ENT accepte les iframes, utiliser :

```html
<iframe src="https://TON_PSEUDO.github.io/activite-balance/" width="100%" height="800" style="border:0;border-radius:12px;" allowfullscreen></iframe>
```


## Version avec raisonnement écrit

Cette version ajoute, pour chaque défi où l’élève doit trouver une masse inconnue, une zone « Mon raisonnement ». Les textes saisis sont sauvegardés localement dans le navigateur de l’élève grâce au localStorage. Le bouton « Télécharger mes réponses » permet d’exporter un fichier texte contenant les valeurs saisies et les raisonnements.

Important : GitHub Pages est un hébergement statique. Il n’envoie pas automatiquement les réponses au professeur. Pour récupérer les raisonnements, demander aux élèves de télécharger le fichier de traces puis de le déposer dans l’ENT.
