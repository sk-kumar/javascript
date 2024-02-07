- https://developer.mozilla.org/en-US/docs/Web/JavaScript
- https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics
- https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics
## Closures
```js
A closure is the combination of a function bundled together (enclosed) with
references to its surrounding state (the lexical environment). In other words, a
closure gives you access to an outer function's scope from an inner function. In
JavaScript, closures are created every time a function is created, at function
creation time.

function makeFunc() {
  const name = "Mozilla";
  function displayName() {
    console.log(name);
  }
  return displayName;
}

const myFunc = makeFunc();
myFunc();

```
## Lexical scoping
```js
function init() {
  var name = "Mozilla"; // name is a local variable created by init
  function displayName() {
    // displayName() is the inner function, that forms the closure
    console.log(name); // use variable declared in the parent function
  }
  displayName();
}
init();
```

```js
Standard objects
Get to know standard built-in objects Array, Boolean, Date, Error, Function, JSON, Math, Number, Object, RegExp, String, Map, Set, WeakMap, WeakSet, and others.

Expressions and operators
Learn more about the behavior of JavaScript's operators instanceof, typeof, new, this, the operator precedence, and more.

Statements and declarations
Learn how do-while, for-in, for-of, try-catch, let, var, const, if-else, switch, and more JavaScript statements and keywords work.

Functions
Learn how to work with JavaScript's functions to develop your applications.

Classes
JavaScript classes are the most appropriate way to do object-oriented programming.
```
