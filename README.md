# Données de Klozy

Ce dépôt sert les données ouvertes de l'application mobile Klozy (services de proximité en accès libre : boîtes aux lettres, boîtes à livres, fontaines, toilettes, poubelles). GitHub Pages les publie à l'adresse <https://bbriker.github.io/klozy-donnees/v1/>.

Les fichiers sont régénérés chaque semaine par un import automatique, puis remplacés d'un seul envoi : le dépôt ne garde qu'un seul commit. **Ne les modifie pas à la main.**

## Contenu

- `v1/catalogue.json` : les familles, les services et les sources.
- `v1/l<ligne>_c<colonne>.json` : un fichier par carré de la grille. Un carré absent n'a aucun point.
- `.nojekyll`, `README.md`, `LICENCE.md`.

## Sources et licences

- OpenStreetMap, « © les contributeurs d'OpenStreetMap », licence ODbL : <https://www.openstreetmap.org/copyright>.
- La Poste, « Liste des boîtes aux lettres de rue… avec heure limite de dépôt », licence ODbL : <https://www.data.gouv.fr/fr/datasets/557ac950c751df3e461d4bfd/>.

Ces données sont filtrées, regroupées par carré et republiées. La base de données Klozy ainsi produite est publiée sous la licence ODbL (voir `LICENCE.md`).
