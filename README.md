# generator-wordpress-s-theme

[Yeoman](http://yeoman.io/) generator for a WordPress starter theme (using [Underscores](https://github.com/Automattic/_s)) with [Gulp](http://gulpjs.com/) and other good stuff. This will install the last version of `_s` (Underscores) and optionally a Gulp setup ready for development and production.

## Installation

##### Install required tools `yo` and `gulp`:

```bash
npm install -g yo gulp
```

##### Install `generator-wordpress-s-theme`:

```bash
npm install -g generator-wordpress-s-theme
```

### Run

##### Create a new directory, and go into:

```bash
mkdir my-new-theme && cd $_
```

##### Run `yo wordpress-s-theme`, and fill the info:

```bash
yo wordpress-s-theme
```

## Gulp usage

- Run `gulp` to watch for changes
- Run `gulp build` to build your theme for production (you will find a `my-new-theme.zip` file in `my-new-theme/dist/`)
- (Optional) Run `gulp build-clean` before `gulp build` to cleanup the `my-new-theme/dist/` folder

## Bower usage
- Run `bower install --save <package>` to install frontend dependencies
- Run `gulp wiredep` to include SCSS file in `/sass/style.scss`

## Versioning

Maintained under the [Semantic Versioning guidelines](http://semver.org/).

## License

[MIT](http://opensource.org/licenses/MIT)
Copyright (c) 2016 [MNyorba]
