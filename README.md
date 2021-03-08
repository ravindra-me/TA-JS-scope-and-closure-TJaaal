TA-JS-scope-and-closure-TJaaal
## What is scope in javascript? 
Scope is a way in which you can restict access of any variable in certain area of the code.

## Types Of scope 
1. Global Scope
2. Function Scope
3. Block Scope


## Global Scope:- 
Identifiers(variable) we can be accessed everywhere within your code that is called global scope.

```js
let firstName = "Ravindra" ;
let lastName = "singh
function getFullName() {
   return `${firstName} ${lastName}`;
}

getFullName() // "Ravindra singh" 

```


## Function Scope:- 
Identifier(variable) we can be accesse everywhere inside the function body and not accessible outside the function body.

```js

function getFullName() {
let firstName = "Ravindra" ;
let lastName = "singh
  return `${firstName} ${lastName}`;
}
console.log(firstName); // error
getFullName() // "Ravindra singh" 

```
## Block Scope:-
When we define Identifier(variable) inside the block that means we define a variable within curly bracket like this `{}` and variable defined by only let and const keyword then it create block scope.
`let` and `const` keyword create block scope.
```js
{
let name = "block scope"
}
console.log(name)//undefined
```
