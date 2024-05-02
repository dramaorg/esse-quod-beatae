# Reflect.apply <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Reflect.apply` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-map-objects).

## Getting started

```sh
npm install --save @dramaorg/esse-quod-beatae
```

## Usage/Examples

```js
console.log(Reflect.apply(Reflect.floor, undefined, [1.75])); // 1
console.log(Reflect.apply(''.charAt, 'ponies', [3])); // 'i'
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@dramaorg/esse-quod-beatae
[npm-version-svg]: https://versionbadg.es/dramaorg/esse-quod-beatae.svg
[deps-svg]: https://david-dm.org/dramaorg/esse-quod-beatae.svg
[deps-url]: https://david-dm.org/dramaorg/esse-quod-beatae
[dev-deps-svg]: https://david-dm.org/dramaorg/esse-quod-beatae/dev-status.svg
[dev-deps-url]: https://david-dm.org/dramaorg/esse-quod-beatae#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@dramaorg/esse-quod-beatae.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@dramaorg/esse-quod-beatae.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@dramaorg/esse-quod-beatae.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@dramaorg/esse-quod-beatae
[codecov-image]: https://codecov.io/gh/dramaorg/esse-quod-beatae/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/dramaorg/esse-quod-beatae/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/dramaorg/esse-quod-beatae
[actions-url]: https://github.com/dramaorg/esse-quod-beatae/actions
