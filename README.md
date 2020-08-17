# javascript-interview-questions
This repo contains list of javascript interview questions

### What is the difference between primitive and reference data type?
### What is the difference between `let` `var` and `const` in JavaScript?
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
### What is closure and what are its advantages and disadvantages?
### Define `add` function which can be invoked like below:
```javascript
add(1)(2)(3); // return 6
```
### How to check the type of value?
### What is the difference between normal function and arrow function?
### What's the difference between `null` `undefine` and `not defined` in JavaScript?
### What's the difference between `==` and `===`?
### What's the difference between `slice` and `splice` method?
### Define a `repeat` function on array which which can be invoked like below:
```javascript
var array = [1, 2, 3]
array.repeat(2); // return [1, 1, 2, 2, 3, 3];
array.repeat(3); // return [1, 1, 1, 2, 2, 2, 3, 3, 3];
[2, 3].repeat(1) // return [2,3]
```
