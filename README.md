# custom-media-queries

> Some custom media queries shortcuts

## Install

	$ npm install cssrecipes-custom-media-queries

## Usage

```css
@media (--viewport-max-s) {
	/* rules here will be active when viewport will be <= "s" size */
}
@media (--viewport-min-s) {
	/* rules here will be active when viewport will be > "s" size */
}
```

### Available custom media queries

#### `--viewport-max-s` <= 30em

#### `--viewport-min-s` > 30em

#### `--viewport-max-m` <= 50em

#### `--viewport-min-m` > 50em

#### `--viewport-max-l` <= 65em

#### `--viewport-min-l` > 65em

#### `--viewport-max-xl` <= 80em

#### `--viewport-min-xl` > 80em

---

## Testing

_Requires [nodejs](http://nodejs.org)_

To generate a build:

	npm run build

To generate the testing build.

	$ npm run build-test

Basic visual tests are in `test/index.html`.


## Contributing

Work on a branch, install dev-dependencies, respect coding style & run tests before submitting a bug fix or a feature.

    $ git clone https://github.com/cssrecipes/custom-media-queries.git
    $ git checkout -b patch-1
    $ npm install
    $ npm test

## [Changelog](CHANGELOG.md)

## [License](LICENSE)
