# Mosaïque

Application web progressive statique, prévue pour GitHub Pages.

## Publication
1. Créer un dépôt GitHub nommé `mosaique`.
2. Déposer le contenu de ce dossier à la racine du dépôt.
3. Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.

## Fonctionnement actuel
- Parcours en trois étapes : choix Enfants/Adultes, sélection de profils (multi-choix), tableau de bord transversal.
- Fiches de psychoéducation adaptées aux profils sélectionnés.
- Journaux émotionnels, sommeil, suivi personnel, préparation de rendez-vous, planning et outils.
- Stockage local au navigateur, export/import JSON.
- Code à quatre chiffres optionnel (verrou d'accès simple).

## Limites importantes
Le code PIN actuel n'est PAS un chiffrement. Les données locales ne sont pas synchronisées et peuvent être perdues si les données du navigateur sont effacées. Ne pas y saisir de données cliniques ou identifiantes avant audit de sécurité et de conformité. Cette version est une base fonctionnelle à compléter et à tester, pas une reproduction à l'identique de ParentsZen.
