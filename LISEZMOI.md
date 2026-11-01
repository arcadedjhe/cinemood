# CinéMood

Application web installable pour choisir un film pour les enfants (genre, univers, ambiance, style, époque, âge).
Elle fonctionne hors ligne une fois installée. Les données (liste de films, critères, films vus) sont enregistrées dans le navigateur de l'appareil.

## Publier sur GitHub Pages

1. Créez un dépôt public sur github.com (par exemple `cinemood`).
2. Dans le dépôt : « Add file », « Upload files », puis déposez **tout le contenu** de ce dossier (index.html, manifest.webmanifest, sw.js, .nojekyll, dossiers fonts et icons). Validez avec « Commit changes ».
3. « Settings », « Pages » : source « Deploy from a branch », branche `main`, dossier `/ (root)`, puis « Save ».
4. Au bout d'une à deux minutes, l'adresse `https://VOTRE-NOM.github.io/cinemood/` est en ligne.

## Installer sur Android

Ouvrez l'adresse dans Chrome, menu (trois points), « Installer l'application » ou « Ajouter à l'écran d'accueil ».

## Mettre à jour

Remplacez les fichiers dans le dépôt. Changez aussi la ligne `const VERSION = 'cinemood-v1'` dans `sw.js` (par exemple `cinemood-v2`) pour que les téléphones récupèrent la nouvelle version.
