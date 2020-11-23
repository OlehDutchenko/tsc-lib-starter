# `lib-name`

![Typescript first](https://img.shields.io/badge/TypeScript-First-blue)
[![BSD-3-Clause License badge](https://img.shields.io/github/license/lib-org/lib-name)](https://github.com/lib-org/lib-name/blob/master/LICENSE)
[![NPM package badge](https://img.shields.io/badge/npm-install-orange.svg)](https://www.npmjs.com/package/lib-name)
![Test and Build status badge](https://github.com/lib-org/lib-name/workflows/Test%20and%20Build/badge.svg)

_Description_

## Coverage

| Statements                | Branches                | Functions                | Lines                |
| ------------------------- | ----------------------- | ------------------------ | -------------------- |
| ![Statements](https://img.shields.io/badge/Coverage-100%25-brightgreen.svg) | ![Branches](https://img.shields.io/badge/Coverage-100%25-brightgreen.svg) | ![Functions](https://img.shields.io/badge/Coverage-100%25-brightgreen.svg) | ![Lines](https://img.shields.io/badge/Coverage-100%25-brightgreen.svg) |

## Table of Content:

1. [Usage](#usage)
    1. [Install npm package](#install-npm-package)
    1. [Import to your codebase](#import-to-your-codebase)
1. [API](#api)
    1. [Properties](#properties)
    1. [Methods](#methods)

## Usage

### Install npm package

```bash
npm i lib-name
```

### Import to your codebase

By default, we distribute our lib as is - original TypeScript files, without transpiling to ES5 or ES6.

```ts
// Import original ts code
// but requires to be not exclude in `node_modules`.
// Check your `tsconfig.json`
import libName from 'lib-name';
```

You can import compiled files from special folders.

```js
// ES6: const, let, spread, rest and other modern JavaScript features
// but requires to be not exclude in `node_modules`.
// Check your `babebl-loader` (if your use webpack as bandler)
import libName from 'lib-name';
// or ES5: no ES6 features but ready for use as is, without transpiling
import libName from 'lib-name';
```

---

## API

### Properties

_describe_

### Methods

_describe_
