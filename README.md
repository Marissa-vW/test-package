# test-package
Practicing npm package creation

![npm (scoped)](https://img.shields.io/npm/v/@marissa.vw/test-package?style=flat-square)

[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@marissa.vw/test-package)](https://www.npmjs.com/package/@marissa.vw/test-package)

Removes all spaces from a string.

## Install

```
$ npm install @marissa.vw/tiny
```

## Usage

```js
const tiny = require("@marissa.vw/test-package");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
