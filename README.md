# HANDY MIRROR - Règles

![Logo](https://github.com/alain-guillon-it/HandyMirror-Documents/blob/main/logo/HM.jpg)

## Outils afin de réaliser à bien le projet IOT

-   [] Vitre ou plexiglass sans tain
-   [] Consommation de plusieurs services (API)
-   [] Un écran LCD (HDMI 2.0)
-   [x] Utiliser le Rapsberry PI Model 4
-   [x] Disposer d'un serveur embarqué
-   [x] Communiquer avec un serveur distant sous (Linux - Raspbian)
-   [x] Visual Studio Code, JetBrains (PhpStorm), GitHub CodeSpaces.
    -   [x] **Alain** : Visual Studio Code
    -   [x] **Maher** : JetBrains (PhpStorm)
    -   [x] **Sophie** : Visual Studio Code
    -   [x] **Tarek** : Visual Studio Code

## Les technologies à utiliser pour HandyMirror (Fil rouge)

-   HTML,CSS,JS + Framwork React
-   Pré-processeur CSS : Sass
-   PHP 8.1 et framwork recommandée (Symphony)
-   Composer
-   Base de donnée via MongoDb + ORM / ODM Doctrine

-   Micro Services eventuels ( technologies libre )

## Important

1. Impératif, **chacun doit impérativement fork les projets**
2. Créer plusieurs branche sur son **fork** afin de bosser dessus,
    1. **main** _La branche principal que vous allez push et merge avec vos branches_
    2. **feature** _La branche qui te permettra de tester une nouvelle fonctionnalité_
    3. **test** _La branche qui te servira à tester tes modifications avant de merger celles-ci avec ta branche main_
    4. **patch** _Cette branche te servira au cas où si tu as un bug à corriger rapidement_
    5. **hotfix** _Cette branche te servira au cas où il y a un bug critique a corriger_
3. **Respecter la syntaxe pour les commits** à voir juste après.
4. Merger vers la branche principale (main) tes modifications
5. Push sur ton fork tes modifications
6. Faire une pullrequest (PR) à partir de ton fork

## Normalisation des commits

Cette section est super importante pour garder des commits propres.
**Attention, aucun commit ne seras écrit avec des majuscules, tout seras en minuscule sauf exception (camelCase ou nom d'une classe)**

**On va se forcer à garder des README en Français, mais l'intégralité du code ainsi que des commits seront en ANGLAIS**

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
