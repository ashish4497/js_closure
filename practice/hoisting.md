## Hoisting Exercises

1. If the code is `valid` what will be the output and if `invalid` what will be the error. Write the error message.

```js
console.log(animal);
var animal = "monkey";
// Output or Error Message
```
output monkey; becouse define in global scope

```js
console.log(animal);
let animal = "monkey";
// Output or Error Message
```
animlan no define

```js
console.log(animal);
const animal = "monkey";
// Output or Error Message
```
animlan no define
```js
  function sayHello(msg) {
    alert(msg);
  }
  sayHello("Hey Everyone");
// Output or Error Message
```
"Hey Everyone"

```js
sayHello("Hey Everyone");
function sayHello(msg) {
  alert(msg);
}

not called 
// Output or Error Message
```

```js
sayHello("Hey Everyone");
var sayHello = msg => {
  alert(msg);
};
// Output or Error Message
```
  not call becouse call first then define 
```js
sayHello("Hey Everyone");
let sayHello = msg => {
  alert(msg);
};
```
 not call becouse call first then define 
