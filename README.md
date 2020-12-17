# test-package
Practicing npm package creation

![npm (scoped)](https://img.shields.io/npm/v/@marissa.vw/test-package?style=flat-square)

[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@marissa.vw/test-package)](https://www.npmjs.com/package/@marissa.vw/test-package)

Removes all spaces from a string.

## Install

```
$ npm install @marissa.vw/test-package
```

## Usage

```js
const test = require("@marissa.vw/test-package");

test("So much space!");
//=> "Somuchspace!"

test(1337);
//=> Uncaught TypeError: Test wants a string!
//    at test (<anonymous>:2:41)
//    at <anonymous>:1:1
```
