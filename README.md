# @patrtorg/a-rem-dignissimos <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Does this JS environment support the `name` property on functions?

## Example

```js
var functionsHaveNames = require('@patrtorg/a-rem-dignissimos');
var assert = require('assert');

assert.equal(functionsHaveNames(), true); // will be `false` in IE 6-8
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@patrtorg/a-rem-dignissimos
[npm-version-svg]: https://versionbadg.es/inspect-js/@patrtorg/a-rem-dignissimos.svg
[deps-svg]: https://david-dm.org/inspect-js/@patrtorg/a-rem-dignissimos.svg
[deps-url]: https://david-dm.org/inspect-js/@patrtorg/a-rem-dignissimos
[dev-deps-svg]: https://david-dm.org/inspect-js/@patrtorg/a-rem-dignissimos/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@patrtorg/a-rem-dignissimos#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@patrtorg/a-rem-dignissimos.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@patrtorg/a-rem-dignissimos.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@patrtorg/a-rem-dignissimos.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@patrtorg/a-rem-dignissimos
[codecov-image]: https://codecov.io/gh/inspect-js/@patrtorg/a-rem-dignissimos/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@patrtorg/a-rem-dignissimos/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@patrtorg/a-rem-dignissimos
[actions-url]: https://github.com/patrtorg/a-rem-dignissimos/actions
