# Generator-StanLee-WPTheme

[Yeoman](http://yeoman.io/) generator for a WordPress starter theme (using [StanLee](https://github.com/tomtomgo92/StanLee)) with [Gulp](http://gulpjs.com/) and other good stuff. This will install the last version of `StanLee` and optionally a Gulp setup ready for development and production.

Générateur [Yeoman](http://yeoman.io/) pour un thème de démarrage de WordPress (Utilisant [StanLee](https://github.com/tomtomgo92/StanLee)). Utilise Gulp](http://gulpjs.com/) et d'autres bonnes choses. Cela permet d'installer la dernière version de `StanLee` et optionnellement une configuration de Gulp prêt au développement et la production.


## Installation


##### Install required tools `yo` and `gulp`:
##### Installer les outils `yo` et `gulp`:

```bash
npm install -g yo gulp
```


##### Install `generator-stanlee-wptheme`:
##### Installer `generator-stanlee-wptheme`:

```bash
npm install -g generator-stanlee-wptheme
```


### Run
### Exécuter


##### Create a new directory, and go into:
##### Créez un nouveau répertoire et aller dedans:

```bash
mkdir my-new-theme && cd $_
```


##### Run `yo stanlee-wptheme`, and fill the info:
##### Exécuter `yo stanlee-wptheme`, et remplir les informations:

```bash
yo stanlee-wptheme
```


## Gulp usage
## Utilisation de Gulp

- Run `gulp` to watch for changes
- Exécuter `gulp` pour voir les changements

- Run `gulp build` to build your theme for production (you will find a `my-new-theme.zip` file in `my-new-theme/dist/`)
- Exécuter `gulp build` pour creer un fichier de production (Vous trouverez un fichier `.zip` dans le dossier `./dist/`

- (Optional) Run `gulp build-clean` before `gulp build` to cleanup the `my-new-theme/dist/` folder
- (Option) Exécuter `gulp build-clean` avant `gulp build` pour vider le dossier `./dist/`


## Bower usage
## Utilisation de Bower

- Run `bower install --save <package>` to install frontend dependencies
- Exécuter `bower install --save <package>` pour installer les dépendances frontend

- Run `gulp wiredep` to include SCSS file in `/sass/style.scss`
- Exécuter `gulp wiredep` pour inclure un fichier SCSS dans `/sass/style.scss`

## License
## Licence

[MIT](http://opensource.org/licenses/MIT)
Copyright (c) 2016 [Thomas & Mathilde]
