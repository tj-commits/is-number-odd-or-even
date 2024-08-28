# is-number-odd-or-even
=======================================

At least 99% of the time, any number can be odd or even. This uncertainty can be eliminated with `is-number-odd-or-even`. As it sports an incredibly fast, open-ended API, you can solve all even or odd related problems with only 1 line.
***

### List of features

*   [x] See if a number is odd or even
*   [x] Output useful logs if logging is enabled while doing stuff

### Download & Installation

```shell
$ npm i is-number-odd-or-even
```

### Usage
Just import the library and pass in two arguments: the value that you want to check is odd or even, and a boolean whether to output useful logs!

### Code Demo

Importing
```js
const isOddOrEven = require("is-number-odd-or-even")
```

Example usage:
```js
const isOddOrEven = require("is-number-odd-or-even")
const test1 = isOddOrEven(1, false) // outputs no logs because logging is disabled
const test2 = isOddOrEven(Infinity, true) // outputs logs because logging is enabled
console.log(test1) // true
console.log(test2) // false (because infinity is not odd or even)
```

### License

    This project is licensed under the MIT License