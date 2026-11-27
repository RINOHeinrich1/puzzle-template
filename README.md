# Puzzle Template — ONIR CMS

Template visuel Puzzle pour ONIR CMS.

## Version courante

- `1.1.0-beta.12`
- Contrat : Editor V2
- Archive : `puzzle-1.1.0-beta.12.onirtech-template`

## Contenu

- `onirtech.template.json` : manifeste et métadonnées d’édition ;
- `index.js` : rendu Web Component ;
- `preview.png` : aperçu ;
- `skills/` : skills IA installés avec la version ;
- archive installable.

## Règles

- Aucune logique Puzzle dans le cœur ONIR CMS.
- Les identifiants de collection sont techniques et générés par l’hôte.
- Les champs sans effet pour un composant sont masqués via `fields[].visibleWhen`.
- Les types d’enfants autorisés sont déclarés dans `editor.insertion`.
- Toute modification incrémente la version et produit une nouvelle archive.

## Skills IA

La version embarque :

- `puzzle-page-menu` : création de page et d’entrée de menu ;
- `puzzle-style-button` : styles de boutons et copies locales ;
- `puzzle-content-edit` : édition de textes et médias ;
- `puzzle-structure` : placements, visibilité, actions et styles partagés.

Les skills sont déclarés dans `onirtech.template.json` via `aiSkills` et installés
avec l’archive. Ils ne sont jamais chargés depuis une source externe.

## Installation

Importer l’archive `.onirtech-template` dans ONIR CMS, puis sélectionner la version sur le lien.
