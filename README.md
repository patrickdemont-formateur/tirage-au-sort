# Roulette de la classe

Application web de tirage au sort, en un seul fichier (`index.html`), sans installation ni dépendance.

## Mettre en ligne sur GitHub Pages

1. Sur GitHub, créez un dépôt (par exemple `roulette`), en public.
2. Cliquez sur **Add file > Upload files**, déposez `index.html` (et ce `README.md`), puis **Commit changes**.
3. Ouvrez **Settings > Pages**. Dans « Build and deployment », choisissez **Deploy from a branch**, la branche `main` et le dossier `/ (root)`, puis **Save**.
4. Après une à deux minutes, l'application est disponible à l'adresse `https://VOTRE-IDENTIFIANT.github.io/roulette/`.

## Utilisation

- **Lancer la roue** (ou touche Espace) : tire un prénom au hasard.
- **Tirage sans remise** : le gagnant sort de la roue au tirage suivant.
- **Importer une liste** : collez des cellules Excel ou un tableau Word.
  - Les colonnes multiples peuvent être assemblées (Prénom Nom) ou réduites à la première.
  - Les puces, numéros, guillemets, doublons et colonnes de simples numéros sont nettoyés automatiquement.
  - On peut remplacer la liste actuelle ou y ajouter des noms.
- **Liste des élèves** : modifiable à la main (un prénom par ligne), puis « Appliquer la liste ».

## Maintenance

Aucune : pas de serveur, pas de base de données, pas de bibliothèque externe. Pour changer la liste par défaut, modifiez la ligne `var DEFAULT = [...]` dans `index.html`.
