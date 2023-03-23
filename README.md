# Project IOT connected mirror and ecodesign thread (GreenIT)

![Capture d'écran du rendu de mon travail en ce mercredi 22/03/2023](https://github.com/alain-guillon-it/IotMirroir/blob/main/Documents/screen_test_magic_mirror/screen_capture_test_alain.png)

## Les outils afin de réaliser à bien le projet IOT

- [x] Utiliser le Rapsberry PI Model 4
- [x] Un écran LCD
- [] Vitre ou plexiglass sans tain
- [x] Disposer d'un serveur embarqué
- [] Consommation de plusieurs services (API)
- [x] Communiquer avec un serveur distant sous (Linux - Raspbian)
- [x] Visual Studio Code, JetBrains (PhpStorm), GitHub CodeSpaces.
  - [x] **Alain** : Visual Studio Code
  - [x] **Maher** : JetBrains (PhpStorm)
  - [x] **Sophie** : Visual Studio Code
  - [x] **Tarek** : Visual Studio Code

## Les technologies utilisés pour le fil rouge

- HTML,CSS,JS + Framwork React
- Pré-processeur CSS : Sass
- PHP 8.1 et framwork recommandée (Symphony)
- Composer
- Base de donnée via MongoDb + ORM / ODM Doctrine

- Micro Services eventuels ( technologies libre )

## Important

1. Impératif, **forker chacun des projets**
2. Créer plusieurs branche sur son **fork** afin de bosser dessus,
   1. **main** _La branche principal que vous allez push et merge avec vos branches_
   2. **feature** _La branche qui te permettra de tester une nouvelle fonctionnalité_
   3. **test** _La branche qui te servira à tester tes modifications avant de merger celles-ci avec ta branche main_
   4. **patch** _Cette branche te servira au cas où si tu as un bug à corriger rapidement_
   5. **hotfix** _Cette branche te servira au cas où il y a un bug critique a corriger_
3. **Respecter la syntaxe pour les commits** à voir juste après.
4. Merger vers la branche principale (main) tes modifications
5. Push sur ton fork tes modifications
6. Faire une pullrequest à partir de ton fork

## Normalisation des commits

Cette section est super importante pour garder des commits propres.
**Attention, aucun commit ne seras écrit avec des majuscules, tout seras en minuscule sauf exception (camelCase ou nom d'une classe)**

```sh
# Ajout d'une nouvelle feature
git commit -m "feature: title" -m "content of new feature"

# Correction d'une feature critique avec un bug
git commit -m "hofix: title" -m "content of the resolve problem"

# Correction mineur d'un problème
git commit -m "patch: title" -m "content of the path at used"

# Test de plusieurs changements à venir
git commit -m "test: title" -m "content of test at to use"
```
