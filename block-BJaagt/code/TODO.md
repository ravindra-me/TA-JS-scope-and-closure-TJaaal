Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

Example:

```js
function hello() {
  var username = 'Arya';
}
console.log(useranme); // Reference Error username is not defined
```

In above code we are looking for the variable named `usename`. There is no variable named `username` in the global scope. The variable is inside the function named `hello` and we can't access the variable defined inside a function from outside.

The above code will throw an error `Reference Error username is not defined`.

2. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
{
  const username = 'Arya';
}
console.log(useranme); // Reference Error username is not defined
```
In above code we are looking for the variable named `usename`. There is no variable named `username` in the global scope. The variable is inside the object so  we can't access the variable defined inside a function from outside.

The above code will throw an error `Reference Error username is not defined`.

3. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  let username = 'Arya';
}
console.log(useranme); // `Reference Error username is not defined`
```
In above code we are looking for the variable named `usename`. There is no variable named `username` in the global scope. The variable is inside the block so  we can't access the variable defined inside a function from outside.

The above code will throw an error `Reference Error username is not defined`.

4. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  var username = 'Arya';
}
console.log(useranme); // Reference Error username is not defined

```
In above code we are looking for the variable named `usename`. There is no variable named `username` in the global scope. var create "function" scope  so  we can't access the variable defined inside a function from outside.

The above code will throw an error `Reference Error username is not defined`.

5. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
if (true) {
  var username = 'Arya';
}
console.log(useranme); // John
```
In above code we are looking for the variable named `usename`. There is  variable named `username` in the global scope.  we can access the variable `username`.

The above code will throw an error `Reference Error username is not defined`.

6. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
if (true) {
  let username = 'Arya';
}
console.log(useranme); // Uncaught SyntaxError Indentifer username has already been declared
```

7. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
function sayHello() {
  let username = 'Arya';
}
sayHello();
console.log(useranme); // Uncaught SyntaxError Indentifer username has already been declared


```
In above code we are looking for the variable named `usename`. There is variable name `username` define in the globle scope but we are also define again same name of variable so is showing error 

8. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (var i = 0; i < 10; i++) {
  console.log(i, 'First'); // 0 "First"
// 1 "First"
 //2 "First"
 //3 "First"
 //4 "First"
 //5 "First"
 //6 "First"
 //7 "First"
 //8 "First"
 //9 "First"
 //10 "First"

}
console.log(i, 'Second'); // 10 "second"
```
i is accessable in globale 

9. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (let i = 0; i < 10; i++) {
  console.log(i, 'First'); // 0 "First"
// 1 " First"
//2 "First"
//3 "First"
//4 "First"
//5 "First"
//6 "First"
//7 "First"
//8 "First"
//9 "First"
//10 "First"

}
console.log(i, 'Second'); // ReferenceError i is not defined 
```
because let create block scope
