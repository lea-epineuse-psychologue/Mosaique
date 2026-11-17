# Mosaïque — version actuelle

Application web progressive statique, prévue pour GitHub Pages.

## Publication / mise à jour
Déposer **tous les fichiers de ce dossier à la racine** du dépôt GitHub, en remplaçant les fichiers existants :
- `index.html`
- `sw.js`
- `manifest.webmanifest`
- `icon-192.png` et `icon-512.png`
- `NOTICE-ET-SECURITE.md`
- `README.md`
- `.nojekyll`

Dans GitHub : Settings → Pages → Deploy from a branch → `main` → `/(root)`.

Après validation, recharger le site. Le service worker est passé à `mosaique-v3` pour invalider l'ancien cache.

## Rubriques incluses dans cette version
- Bien-être : respiration guidée avec bulle animée et rythmes au choix, pause guidée avec minuteur, ancrage sensoriel 5-4-3-2-1.
- Sommeil : échelle visuelle en six niveaux et historique sous forme de points colorés.
- Gestion des émotions : choix visuel des émotions, curseur d'intensité et historique coloré.
- Les autres rubriques et espaces présents dans la version précédente sont conservés.

## Données et sécurité
Les données sont stockées localement dans le navigateur. Elles ne sont pas synchronisées entre appareils et peuvent être perdues si les données du navigateur sont effacées. Le code PIN à quatre chiffres est un verrou d'accès simple, pas un chiffrement. Ne pas y saisir de données cliniques ou identifiantes.
