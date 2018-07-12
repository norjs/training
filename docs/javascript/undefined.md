---
layout: javascript-page
title: "Undefined - Variables - JavaScript"
permalink: /javascript/undefined
---

### Undefined in JavaScript

`undefined` is a special global variable and a special type which has only one 
state. 

It is intended to be used to describe something that is not defined yet.

```javascript
let enabled = undefined;
```

Also every uninitialized variable is automatically set as `undefined`.

```javascript
let enabled;

if (enabled === undefined) {
	// This code will be executed
}
```

If you access an object property which does not exist the 
returned value will also have `undefined` as it's value:

```javascript
let opts = {};
let enabled = opts.enabled;
if (enabled === undefined) {
	// This code will be executed
}
```
