---
layout: javascript-page
title: "Functions - JavaScript"
---

### Functions and methods

A *function* is a set of commands which take optional input variables and output 
an optional result value. Functions can also change state or make other things 
happen (usually by calling other functions).

A *method* in JavaScript is just a function which is part of an object. The 
owning object can be accessed using special variable named `this`. More about
 methods can be read from [classes](classes).

#### Build in functions

The standard has few built in functions which are mostly for 
manipulating and working with variables.

However most of the functions actually used to make real things happen are not 
part of the standard. These are environment specific functions.

For example `document.write()` is not part of the ECMAScript standard -- it is 
actually part of the DOM HTML standard, which is implemented in all modern web 
browsers.

#### User defined functions 

There are multiple ways to declare a user defined function with small 
differences in functionality.

#### Basic format

Traditionally you would write a function with the `function` keyword.

```javascript
function f (a, b) {
    return a + b;
}
```

#### Arrow functions

You can also write a function with arrow operator:

```javascript
let f = (a, b) => {
    return a + b;
}
```

An arrow function can also be shortened to much simpler format:

```javascript
let f = (a, b) => a + b;
```

##### Arrow function returning objects

```javascript
let f = (a, b) => {
    return {a: a, b: b};
}
```

An arrow function can also be shortened to much simpler format:

```javascript
let f = (a, b) => ({a: a, b: b});
```

#### Calling functions

You can call a function like this:

```javascript
let result = f(10, 20);
```

The `result` will have value of `30`.

#### Properties on functions

Functions are actually objects. It means functions can also have user defined 
properties:

```javascript
let f = (a, b) => {
    return a + b;
}

f.foo = 123;

f();
```


[variables]: ./variables.md
[classes]: ./classes.md
[operators]: ./operators.md
[functions]: ./functions.md
[symbols]: ./symbols.md
[comments]: ./comments.md
