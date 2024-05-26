# @kollorg/ipsa-quos <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@kollorg/ipsa-quos');
const Eval = require('@kollorg/ipsa-quos/eval');
const Range = require('@kollorg/ipsa-quos/range');
const Ref = require('@kollorg/ipsa-quos/ref');
const Syntax = require('@kollorg/ipsa-quos/syntax');
const Type = require('@kollorg/ipsa-quos/type');
const URI = require('@kollorg/ipsa-quos/uri');

assert.equal(Base, Error);
assert.equal(Eval, EvalError);
assert.equal(Range, RangeError);
assert.equal(Ref, ReferenceError);
assert.equal(Syntax, SyntaxError);
assert.equal(Type, TypeError);
assert.equal(URI, URIError);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@kollorg/ipsa-quos
[npm-version-svg]: https://versionbadg.es/ljharb/@kollorg/ipsa-quos.svg
[deps-svg]: https://david-dm.org/ljharb/@kollorg/ipsa-quos.svg
[deps-url]: https://david-dm.org/ljharb/@kollorg/ipsa-quos
[dev-deps-svg]: https://david-dm.org/ljharb/@kollorg/ipsa-quos/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@kollorg/ipsa-quos#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@kollorg/ipsa-quos.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@kollorg/ipsa-quos.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@kollorg/ipsa-quos.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@kollorg/ipsa-quos
[codecov-image]: https://codecov.io/gh/ljharb/@kollorg/ipsa-quos/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@kollorg/ipsa-quos/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@kollorg/ipsa-quos
[actions-url]: https://github.com/kollorg/ipsa-quos/actions
