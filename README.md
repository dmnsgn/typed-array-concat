# concat-typed-array [![Build Status](https://travis-ci.org/dmnsgn/concat-typed-array.svg?branch=master)](https://travis-ci.org/dmnsgn/concat-typed-array) [![Greenkeeper badge](https://badges.greenkeeper.io/dmnsgn/concat-typed-array.svg)](https://greenkeeper.io/)

> Concatenate n typed arrays

Based on this [article](http://www.2ality.com/2015/10/concatenating-typed-arrays.html).

## Install

```
$ npm install --save concat-typed-array
```


## Usage

```js
const concatTypedArray = require('concat-typed-array');

concatTypedArray(Uint8Array, Uint8Array.of(1, 2), Uint8Array.of(3, 4));
//=> Uint8Array [1, 2, 3, 4]
```


## API

### concatTypedArray(resultConstructor, array0, array1, arrayN...)

#### resultConstructor

Type: `constructor`

Returned typed array constructor.

#### arrays

##### ...arrays

Type: `array`<br>

Arrays to concatenate.


## License

MIT © [Axel Rauschmayer](http://www.2ality.com/2015/10/concatenating-typed-arrays.html), [Damien Seguin](https://github.com/dmnsgn)
