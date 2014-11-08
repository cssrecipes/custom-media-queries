# custom-media-queries

> Some custom media queries shortcuts

## Install

```sh
$ npm install cssrecipes-custom-media-queries
```

## Usage

```css
/* for desktop first approch */
@media (--r-maxS) {
  /* rules here will be active when viewport will be <= "s" size */
}

/* for mobile first approch */
@media (--r-minS) {
  /* rules here will be active when viewport will be > "s" size */
}
```

### Available custom media queries

#### `--r-maxS` <= 30em

#### `--r-minS` > 30em

#### `--r-maxM` <= 50em

#### `--r-minM` > 50em

#### `--r-maxL` <= 65em

#### `--r-minL` > 65em

#### `--r-maxXL` <= 80em

#### `--r-minXL` > 80em

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
