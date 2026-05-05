# CLAUDE.md — mon-journal

## Ce que fait cet outil
Journal intime personnel — recueil d'actions, ressentis et réflexions au quotidien.
Usage strictement personnel.

## URL de production
https://jujuem44-lab.github.io/mon-journal/

## Structure du repo
- `index.html` — fichier unique, tout le code est dedans (HTML + CSS + JS)

## Airtable
- **Base :** `appITdhAzHBgYWW1e` (JOURNAL_JUJU)
- **Table Entrées Journal :** `tblz3cnfFrFl27758`

## Sécurité
- Le token Airtable est stocké localement (localStorage) — jamais dans le code GitHub
- Ne jamais hardcoder le token dans index.html

## Règles de développement
- Toujours travailler dans `index.html` — ne jamais créer de fichiers séparés CSS/JS
- Ne jamais modifier les IDs Airtable sans confirmation explicite
- Conserver la logique de stockage du token en localStorage — critique pour la sécurité
- Tester toujours en local avant push (ouvrir index.html dans le navigateur)
- Déploiement : push sur `main` → GitHub Pages se met à jour automatiquement

## Propriétaire
Juju — usage personnel
