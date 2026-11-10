# Pesée des recettes

Petit outil pour peser les ingrédients d'une recette de chocolaterie.

Pour chaque recette : une liste d'ingrédients avec un pourcentage, une quantité finale à produire, et l'outil calcule la quantité à peser (en kg et en g) pour chaque ingrédient.

## Utilisation

Ouvrir `index.html` dans un navigateur (double-clic). Aucune installation, aucun serveur.

- Les recettes sont enregistrées dans le navigateur (localStorage).
- « Ajuster selon le pesé » : si tu as mis trop d'un ingrédient, saisis la quantité réellement pesée et l'outil recalcule la recette d'après le plus grand dépassement.
- Les polices (Bricolage Grotesque, Instrument Sans) se chargent depuis Google Fonts ; sans connexion, la police système est utilisée.

## Publier en ligne (GitHub Pages)

Settings → Pages → Source : « Deploy from a branch », branche `main`, dossier `/ (root)`.
