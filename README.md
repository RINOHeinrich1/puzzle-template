# Puzzle Template — ONIR CMS

Template visuel Puzzle pour ONIR CMS.

## Version courante

- `1.1.0-beta.3`
- Contrat : Editor V2
- Archive : `puzzle-1.1.0-beta.3.onirtech-template`

## Contenu

- `onirtech.template.json` : manifeste et métadonnées d’édition ;
- `index.js` : rendu Web Component ;
- `preview.png` : aperçu ;
- archive installable.

## Règles

- Aucune logique Puzzle dans le cœur ONIR CMS.
- Les identifiants de collection sont techniques et générés par l’hôte.
- Les champs sans effet pour un composant sont masqués via `fields[].visibleWhen`.
- Les types d’enfants autorisés sont déclarés dans `editor.insertion`.
- Toute modification incrémente la version et produit une nouvelle archive.

## Installation

Importer l’archive `.onirtech-template` dans ONIR CMS, puis sélectionner la version sur le lien.
