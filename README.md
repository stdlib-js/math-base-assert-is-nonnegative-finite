<!--

@license Apache-2.0

Copyright (c) 2022 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# isNonNegativeFinite

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Test if a numeric value is a nonnegative finite number.



<section class="usage">

## Usage

To use in Observable,

```javascript
isNonNegativeFinite = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/math-base-assert-is-nonnegative-finite@umd/browser.js' )
```

To vendor stdlib functionality and avoid installing dependency trees for Node.js, you can use the UMD server build:

```javascript
var isNonNegativeFinite = require( 'path/to/vendor/umd/math-base-assert-is-nonnegative-finite/index.js' )
```

To include the bundle in a webpage,

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/math-base-assert-is-nonnegative-finite@umd/browser.js"></script>
```

If no recognized module system is present, access bundle contents via the global scope:

```html
<script type="text/javascript">
(function () {
    window.isNonNegativeFinite;
})();
</script>
```

#### isNonNegativeFinite( x )

Tests if a `numeric` value is a nonnegative finite number.

```javascript
var bool = isNonNegativeFinite( 3.14 );
// returns true

bool = isNonNegativeFinite( -2.0 );
// returns false
```

</section>

<!-- /.usage -->

<section class="notes">

</section>

<!-- /.notes -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/math-base-assert-is-nonnegative-finite@umd/browser.js"></script>
<script type="text/javascript">
(function () {

var bool = isNonNegativeFinite( 5.0 );
// returns true

bool = isNonNegativeFinite( 3.14 );
// returns true

bool = isNonNegativeFinite( 0.0 );
// returns true

bool = isNonNegativeFinite( -2.0 );
// returns false

bool = isNonNegativeFinite( Infinity );
// returns false

bool = isNonNegativeFinite( NaN );
// returns false

})();
</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2022. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/math-base-assert-is-nonnegative-finite.svg
[npm-url]: https://npmjs.org/package/@stdlib/math-base-assert-is-nonnegative-finite

[test-image]: https://github.com/stdlib-js/math-base-assert-is-nonnegative-finite/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/math-base-assert-is-nonnegative-finite/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/math-base-assert-is-nonnegative-finite/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/math-base-assert-is-nonnegative-finite?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/math-base-assert-is-nonnegative-finite.svg
[dependencies-url]: https://david-dm.org/stdlib-js/math-base-assert-is-nonnegative-finite/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/math-base-assert-is-nonnegative-finite/tree/deno
[umd-url]: https://github.com/stdlib-js/math-base-assert-is-nonnegative-finite/tree/umd
[esm-url]: https://github.com/stdlib-js/math-base-assert-is-nonnegative-finite/tree/esm
[branches-url]: https://github.com/stdlib-js/math-base-assert-is-nonnegative-finite/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/math-base-assert-is-nonnegative-finite/main/LICENSE

<!-- <related-links> -->

<!-- </related-links> -->

</section>

<!-- /.links -->
