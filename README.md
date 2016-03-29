Golden Ratio (φ)
===
[![NPM version][npm-image]][npm-url] [![Build Status][build-image]][build-url] [![Coverage Status][coverage-image]][coverage-url] [![Dependencies][dependencies-image]][dependencies-url]

> [Golden ratio][phi].

The [golden ratio][phi] can be defined algebraically as

<!-- <equation class="equation" label="eq:golden_ratio" align="center" raw="\phi = \frac{1 + \sqrt{5}}{2}" alt="Golden ratio"> -->
<div class="equation" align="center" data-raw-text="\phi = \frac{1 + \sqrt{5}}{2}" data-equation="eq:golden_ratio">
    <img src="https://cdn.rawgit.com/const-io/phi/d8d5c67b8d8c10b9c34d9cbf1db90c86fd42ec4a/docs/img/golden_ratio.svg" alt="Golden ratio">
    <br>
    <br>
</div>
<!-- </equation> -->


## Installation

``` bash
$ npm install const-phi
```


## Usage

``` javascript
var PHI = require( 'const-phi' );
```

#### PHI

The [golden ratio][phi-value].

``` javascript
PHI === 1.618033988749895;
```


## Examples

``` javascript
var PHI = require( 'const-phi' );

console.log( PHI );
// returns 1.618033988749895
```

To run the example code from the top-level application directory,

``` bash
$ node ./examples/index.js
```


---
## Tests

### Unit

This repository uses [tape][tape] for unit tests. To run the tests, execute the following command in the top-level application directory:

``` bash
$ make test
```

All new feature development should have corresponding unit tests to validate correct functionality.


### Test Coverage

This repository uses [Istanbul][istanbul] as its code coverage tool. To generate a test coverage report, execute the following command in the top-level application directory:

``` bash
$ make test-cov
```

Istanbul creates a `./reports/coverage` directory. To access an HTML version of the report,

``` bash
$ make view-cov
```


### Browser Support

This repository uses [Testling][testling] for browser testing. To run the tests in a (headless) local web browser, execute the following command in the top-level application directory:

``` bash
$ make test-browsers
```

To view the tests in a local web browser,

``` bash
$ make view-browser-tests
```

<!-- [![browser support][browsers-image]][browsers-url] -->


---
## License

[MIT license](http://opensource.org/licenses/MIT).


## Copyright

Copyright &copy; 2015-2016. The [Compute.io][compute-io] Authors.


[npm-image]: http://img.shields.io/npm/v/const-phi.svg
[npm-url]: https://npmjs.org/package/const-phi

[build-image]: http://img.shields.io/travis/const-io/phi/master.svg
[build-url]: https://travis-ci.org/const-io/phi

[coverage-image]: https://img.shields.io/codecov/c/github/const-io/phi/master.svg
[coverage-url]: https://codecov.io/github/const-io/phi?branch=master

[dependencies-image]: http://img.shields.io/david/const-io/phi.svg
[dependencies-url]: https://david-dm.org/const-io/phi

[dev-dependencies-image]: http://img.shields.io/david/dev/const-io/phi.svg
[dev-dependencies-url]: https://david-dm.org/dev/const-io/phi

[github-issues-image]: http://img.shields.io/github/issues/const-io/phi.svg
[github-issues-url]: https://github.com/const-io/phi/issues

[tape]: https://github.com/substack/tape
[istanbul]: https://github.com/gotwarlost/istanbul
[testling]: https://ci.testling.com

[compute-io]: https://github.com/compute-io/

[phi]: http://en.wikipedia.org/wiki/Golden_ratio
[phi-value]: http://oeis.org/A001622
