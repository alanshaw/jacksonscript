# JacksonScript

What if there was a super simple language for beginners without all the WTF of JavaScript?

## Rules? Yes it does.

* No `undefined`
* No `new`
* No `prototype`
* Block scoped variables (let)
* No function declarations, only function expressions
* Ergo no variable or function hoisting
* Double equals works as triple equals
* Inner function `this` bound correctly
* No NaN

## Goals? Yes it has.

* Compile to JavaScript
* Be JavaScript the best parts
* Do not be WTF

## Examples?

### Hello World

```js
let greet = function (greeting) {
  console.log('Hello ' + greeting)
}

greet('World') // prints "Hello World"
```
