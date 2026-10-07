# Mettre en place ton profil GitHub

GitHub affiche un README sur ton profil seulement s'il se trouve dans un dépôt **public** qui porte **exactement ton nom d'utilisateur** : `snoyy-i/snoyy-i`.

1. Sur github.com, crée le dépôt `snoyy-i` (public), s'il n'existe pas déjà. GitHub te signale que c'est un dépôt spécial : c'est normal.
2. Dépose à la racine : `README.md` et `banner.svg`.
3. Dépose aussi le dossier `.github/workflows/snake.yml` (dans l'interface GitHub : « Add file », « Create new file », tape `.github/workflows/snake.yml` comme nom, puis colle le contenu).
4. Va dans l'onglet **Actions**, ouvre « Serpent des contributions » et clique sur **Run workflow**. Au bout d'une minute, le serpent apparaît sur ton profil, puis il se met à jour tout seul toutes les 12 heures.

Si l'onglet Actions refuse de publier : Settings, Actions, General, « Workflow permissions », coche **Read and write permissions**.

## À savoir

- Les cartes de statistiques viennent de services gratuits (github-readme-stats, streak-stats, activity-graph). Il arrive qu'elles ne s'affichent pas pendant quelques heures quand ces services sont surchargés : ce n'est pas ton README qui est en cause.
- Pour mettre ta propre image à la place de la bannière, dépose-la (par exemple `banner.png`) et remplace `banner.svg` par son nom à la première ligne du README.
- Le compteur de visites démarre à zéro.
