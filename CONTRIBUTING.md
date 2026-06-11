# Guide de Contribution TuneGuess 🎵

Merci de l'intérêt que vous portez à TuneGuess ! Voici quelques directives pour nous aider à maintenir la qualité du code.

## 🚀 Comment contribuer ?

1. **Forkez** le dépôt qui vous intéresse.
2. Créez une branche descriptive : `git checkout -b feat/ajout-mode-survie` ou `fix/bug-audio`.
3. Commitez vos modifications en suivant les conventions (voir ci-dessous).
4. Ouvrez une **Pull Request** (PR) vers la branche `main` ou `develop`.

## 📝 Conventions de Commit

Nous utilisons la convention **Conventional Commits** :
* `feat`: Une nouvelle fonctionnalité (ex: `feat(ui): ajout du bouton skip`)
* `fix`: Une correction de bug (ex: `fix(api): correction du calcul des points`)
* `docs`: Modification de la documentation
* `style`: Changements cosmétiques (indentation, point-virgule, pas de modification de logique)
* `refactor`: Modification du code qui ne corrige ni un bug ni n'ajoute de fonction

## 💻 Stack Technique & Standards

* **TypeScript** obligatoire, pas de `any` sauvage.
* Respectez la configuration **ESLint** / **Prettier** du projet.
* Assurez-vous que l'application tourne correctement sous **Docker** avant de push.
