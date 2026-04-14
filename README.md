# QCM iPhone Web App

Ce dossier est pret pour une publication sur GitHub Pages.

## Fichiers utiles

- `index.html` : l'application
- `manifest.webmanifest` : configuration de la web app installable
- `service-worker.js` : cache hors ligne simple
- `icon.svg` : icone de l'app
- `404.html` : secours pour GitHub Pages

## Publication sur GitHub Pages

1. Cree un depot GitHub.
2. Envoie le contenu de ce dossier a la racine du depot.
3. Sur GitHub, ouvre `Settings > Pages`.
4. Dans `Build and deployment`, choisis :
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - `Folder`: `/ (root)`
5. Attends la publication.

L'URL finale ressemblera a :

`https://TON-PSEUDO.github.io/NOM-DU-DEPOT/`

## Installation sur iPhone

1. Ouvre l'URL GitHub Pages dans Safari sur iPhone.
2. Touche `Partager`.
3. Choisis `Ajouter a l'ecran d'accueil`.

L'app s'ouvrira ensuite comme une mini app en plein ecran.

## Test en local sur Mac

```bash
cd "/Users/valentinhutter/Documents/New project/qcm-iphone-app"
python3 -m http.server 8000
```

Puis ouvre :

`http://localhost:8000`
