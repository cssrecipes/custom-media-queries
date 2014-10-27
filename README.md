# custom-media-queries

> Some custom media queries shortcuts

## Install

```sh
$ npm install cssrecipes-custom-media-queries
```

## Usage

```css
/* for desktop first approch */
@media (--cssr-maxS) {
  /* rules here will be active when viewport will be <= "s" size */
}

/* for mobile first approch */
@media (--cssr-minS) {
  /* rules here will be active when viewport will be > "s" size */
}
```

### Available custom media queries

#### `--cssr-maxS` <= 30em

#### `--cssr-minS` > 30em

#### `--cssr-maxM` <= 50em

#### `--cssr-minM` > 50em

#### `--cssr-maxL` <= 65em

#### `--cssr-minL` > 65em

#### `--cssr-maxXL` <= 80em

#### `--cssr-minXL` > 80em

---

## Testing

To generate a build:

```sh
$ npm run build
```

To generate the testing build.

```sh
$ npm run build-test
```

Basic visual tests are in `test/index.html`.

## Contributing

Work on a branch, install dev-dependencies, respect coding style & run tests before submitting a bug fix or a feature.

```sh
$ git clone https://github.com/cssrecipes/custom-media-queries.git
$ git checkout -b patch-1
$ npm install
$ npm test
```

## [Changelog](CHANGELOG.md)

## [License](LICENSE)
