# random-float [![Build Status](https://travis-ci.com/sindresorhus/random-float.svg?branch=master)](https://travis-ci.com/sindresorhus/random-float)

> Generate a random [float](https://en.wikipedia.org/wiki/Floating_point)

## Install

```
$ npm install random-float
```

## Usage

```js
const randomFloat = require('random-float');

randomFloat(5);
//=> 4.401887938147411

randomFloat(10, 100);
//=> 72.34217455144972
```

## API

### randomFloat(maximum?)

Returns an float from `0` to `maximum`.

### randomFloat(minimum, maximum)

Returns an float from `minimum` to `maximum`.

#### minimum

Type: `number`\
Default: `0`

Minimum float to return.

#### maximum

Type: `number`\
Default: `1`

Maximum float to return.

## Related

- [random-int](https://github.com/sindresorhus/random-int) - Generate a random integer
- [random-item](https://github.com/sindresorhus/random-item) - Get a random item from an array
- [random-boolean](https://github.com/arthurvr/random-boolean) - Get a random boolean
- [random-obj-key](https://github.com/sindresorhus/random-obj-key) - Get a random key from an object
- [random-obj-prop](https://github.com/sindresorhus/random-obj-prop) - Get a random property from an object
- [unique-random](https://github.com/sindresorhus/unique-random) - Generate random numbers that are consecutively unique
- [unique-random-array](https://github.com/sindresorhus/unique-random-array) - Get consecutively unique elements from an array
- [crypto-random-string](https://github.com/sindresorhus/crypto-random-string) - Generate a cryptographically strong random string
