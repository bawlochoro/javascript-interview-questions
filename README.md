# Javascript Interview Questions
This repo contains list of javascript interview questions

## Variables and DataTypes

### What is the difference between primitive and reference data type?
### What is the difference between `let` `var` and `const` in JavaScript?
### What's the difference between `null` `undefined` and `not defined` in JavaScript?
### How to check the type of value?
### What is `this` keyword?
### What is `NaN` in javascript?
### What is the output of the following:
```javascript
console.log(2 + 3);
console.log(2 + '3');

console.log(2 + 3 + 4);
console.log(2 + '3' + 4);
console.log(2 + '3' + '4');

console.log(false + true);
console.log(true + true);
console.log(false + false);
```

## Hoisting

### What is hoisting?
### What is the output of the following:
```javascript
console.log(x);
console.log(y);
console.log(z);

var x = 10;
let y = 10;
const z = 10;
```
## What is the output of the following:
```javascript
f1();
f2();

function f1() {
  console.log(1);
}

var f2 = function() {
  console.log(2);
};
```

## Functions

### What are the different ways to define function in Javascript?
### What is the output of the following:
```javascript
  function f1() {
    return
    {
      a: 1,
      b: 2
    }
  }
  console.log(f1().a);
```
### What is the difference between function, method and constructor?
### What is the difference between normal function and arrow function?
### What is the output of the following:
```javascript
  function f1() {
    console.log(this);
  }
  
  var f2 = () => {
    console.log(this);
  }
  
  f1();
  f2();
  
  var obj = {
    f1: function() {
      console.log(this);
    },
    f2: function() {
      setTimeout(function() {
        console.log(this);
      }, 0);
    },
    f3: function() {
      setTimeout(() => {
        console.log(this);
      }, 0);
    },
  };
  obj.f1();
  obj.f2();
  obj.f3();
```
### What is the difference between `call`, `apply` and `bind` method?
### What is `arguments` keyword?
### What is IIFE (Immediately Invoked Function Expression)?
### What is callback?
### What is the difference between setTimeout and setInterval?
### What is closure and what are its advantages and disadvantages?
### Define `add` function which can be invoked like below:
```javascript
add(1)(2)(3); // return 6
```
### What is the difference between debouncing and throttling?

## Equality Operators

### What is the difference between `==` and `===`?
### What is the output of the following:
```javascript
console.log(2==2);
console.log(2===2);

console.log(2=='2');
console.log(2==='2');

console.log(undefined == null);
console.log(undefined === null);

console.log(NaN == NaN);
console.log(NaN === NaN);

console.log([] == []);
console.log([] === []);

console.log([1, 2, 3] == [1, 2, 3]);
console.log([1, 2, 3] === [1, 2, 3]);

console.log({} == {});
console.log({} === {});
```
## Arrays

### What are the different ways to define array in Javascript? 
### What are the different ways to iterate through array in Javascript? 
### What's the difference between `slice` and `splice` methods?
### Define a `repeat` function on array which which can be invoked like below:
```javascript
var array = [1, 2, 3];
array.repeat(2); // return [1, 1, 2, 2, 3, 3];
array.repeat(3); // return [1, 1, 1, 2, 2, 2, 3, 3, 3];
[2, 3].repeat(1) // return [2, 3]
```
### What is the use of `map`, `filter`, `every`, `some` and `reduce` method in Javascript?

## Objects

### What are the different ways to define objects in Javascript?
### What is the difference between classical inheritance and prototypal inheritance?

## Promise, Async/Await?

### What is promise and how its different from callback?
### Implement polyfill for promise
### What is async/await?

## Others

### Is javascript a single threaded or multi-threaded language?
### What is event loop and how it works?
### What is the output of the following:
```javascript
console.log(1);

console.log(2);

setTimeout(function() {
  console.log(3);
}, 0);

console.log(4);

```
### What is the difference between `async` and `defer` attribute in script tag?
