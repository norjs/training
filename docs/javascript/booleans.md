---
layout: javascript-page
title: "Booleans - Variables - JavaScript"
permalink: /javascript/booleans
---

### Booleans in JavaScript

A *boolean* is a variable type which has two states `true` and `false`.

```javascript
let enabled = false;

if (enabled) {
	// This code will not be executed
}

enabled = true;

if (enabled) {
	// This code will be executed
}
```

The value of a boolean variable can be toggled with `!`-operator:

```javascript
if (!enabled) {
	// This code will not be executed when enabled is true
}
```

### References

 * [Primitives](https://developer.mozilla.org/en-US/docs/Glossary/Primitive)
 * [Boolean object wrapper](https://developer.mozilla
 .org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)