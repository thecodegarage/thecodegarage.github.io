[Home](../../) > [JavaScript](../)

# ES6 Features & Examples

## Reference links

- [w3schools.com ES6 New Features](https://www.w3schools.com/js/js_es6.asp)

## What's New?

- let & const
- Arrow Functions
- For/of
- Map Objects
- Set Objects
- Classes
- Promises
- Symbol
- Default Parameters
- Function Rest Parameter
- String.includes()
- String.startsWith()
- String.endsWith()
- Array.from()
- Array keys()
- Array find()
- Array findIndex()
- New Math Methods
- New Number Properties
- New Number Methods
- New Global Methods
- Iterables object.entries
- JavaScript Modules

## New Feature Examples

### var - let - const

`var` has function scope, while `let` and `const` have block scope:

```javascript
function foo() {
  for (var x = 0; x < 5; x++) {
    console.log(x);
  }
  console.log(x); //no error.  x === 5
}

function bar() {
  for (let x = 0; x < 5; x++) {
    console.log(x);
  }
  console.log(x); //ReferenceError: x is no defined
}

foo();
bar();
```

`const` will not allow reassignment of a variable:

```javascript
const a = 5;
a = 2; //TypeError: Assignment to constant variable.
console.log(a);
```

General rule on usage of `let` and `const`: Use `const` by default, and only `let` if you need to reassign the variable.

### objects

### For/of

For-in is for iterating over properties of an object

For-of is for iterating over items in an array

```javascript
for (var x = 0; x < 10; x++){
}
//ES5 gave us For-Each:
foreach(var item in items){
}
//ES6 gives us For-Of:
for(item of items){
}
```

Benefits of using the For-Of Loop are?

### this

### Arrow functions

- Arrow functions provide a shorter syntax compared to function expressions
- They lexically bind the this value.
- Are always anonymous
- if using an expression after an arrow, the return is implicit. (no return is required)
- function (args) {expression} becomes: arguments => expression

### Arrow functions and this

### Array.map()

### Array.reduce()

### Array.

### Object Destructuring

### Classes

### Inheritance

### Named and Default Exports

### ES6: Classes

### ES6: Hoisting

### ES6: Static Methods

### ES6: This

### ES6: Private Members using Symbols

### ES6: Private Members using WeakMaps

### ES6: Getters and Setters

### ES6: Inheritance

### ES6: Method Overriding

### ES6: Cheat Sheet

### ES6: Modules

### ES6: Common JS Modules

### ES6: Tooling

### ES6: Babel

### ES6: Webpack

###
