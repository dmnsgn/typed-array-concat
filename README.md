# typed-array-concat

[![npm version](https://img.shields.io/npm/v/typed-array-concat)](https://www.npmjs.com/package/typed-array-concat)
[![stability-stable](https://img.shields.io/badge/stability-stable-green.svg)](https://www.npmjs.com/package/typed-array-concat)
[![npm minzipped size](https://img.shields.io/bundlephobia/minzip/typed-array-concat)](https://bundlephobia.com/package/typed-array-concat)
[![dependencies](https://img.shields.io/librariesio/release/npm/typed-array-concat)](https://github.com/dmnsgn/typed-array-concat/blob/main/package.json)
[![types](https://img.shields.io/npm/types/typed-array-concat)](https://github.com/microsoft/TypeScript)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-fa6673.svg)](https://conventionalcommits.org)
[![styled with prettier](https://img.shields.io/badge/styled_with-Prettier-f8bc45.svg?logo=prettier)](https://github.com/prettier/prettier)
[![linted with eslint](https://img.shields.io/badge/linted_with-ES_Lint-4B32C3.svg?logo=eslint)](https://github.com/eslint/eslint)
[![license](https://img.shields.io/github/license/dmnsgn/typed-array-concat)](https://github.com/dmnsgn/typed-array-concat/blob/main/LICENSE.md)

Concatenate n typed arrays.

[![paypal](https://img.shields.io/badge/donate-paypal-informational?logo=paypal)](https://paypal.me/dmnsgn)
[![coinbase](https://img.shields.io/badge/donate-coinbase-informational?logo=coinbase)](https://commerce.coinbase.com/checkout/56cbdf28-e323-48d8-9c98-7019e72c97f3)
[![twitter](https://img.shields.io/twitter/follow/dmnsgn?style=social)](https://twitter.com/dmnsgn)

Based on [Axel Rauschmayer's article](http://www.2ality.com/2015/10/concatenating-typed-arrays.html).

## Installation

```bash
npm install typed-array-concat
```

## Usage

```js
import typedArrayConcat from "typed-array-concat";
typedArrayConcat(Uint8Array, Uint8Array.of(1, 2), Uint8Array.of(3, 4));
//=> Uint8Array [1, 2, 3, 4]
```

## API

<!-- api-start -->

<a name="module_typedArrayConcat"></a>

## typedArrayConcat

<a name="exp_module_typedArrayConcat--typedArrayConcat"></a>

### typedArrayConcat(ResultConstructor, ...arrays) ⇒ <code>TypedArray</code> ⏏

Concatenate n typed arrays

**Kind**: Exported function

| Param             | Type                    | Description                      |
| ----------------- | ----------------------- | -------------------------------- |
| ResultConstructor | <code>TypedArray</code> | Returned typed array constructor |
| ...arrays         | <code>TypedArray</code> | Arrays to concatenate            |

<!-- api-end -->

## License

MIT. See [license file](https://github.com/dmnsgn/typed-array-concat/blob/main/LICENSE.md).
