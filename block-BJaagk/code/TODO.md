1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let percentage = function (marks, total) {
  return (marks * 100) / 100;
}

let percentage =  (marks, total) => {
  return (marks * 100) / 100;
}

```


2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your answer

let percentage =  (marks, total) => {
  return (marks * 100) / 100;
}

percentage (marks, total) {
  return (marks * 100) / 100;
}

```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

function percentage(marks, total) {
  return (marks * 100) / total;
};

```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};

function percentage(marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};

function percentage(marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => (marks * 100) / total;

function percentage(marks, total) {
  return (marks * 100) / total;
};
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

4. Why is a function call an expression in JavaScript?

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // valid because function is a object and object is store in a variable that type function is call function expression
five = add; // vaild because add is function refrence 
five = five(10, 11); // vaild it is function expression 
five = function () {
  return 'Hello';
}; // Answer  VALID function is a object and object is expression variable can store expression 
```

6. What is the difference between function definition and function call? Explain with an example.
```js
// function definition
function name() {
  return "ravindra"
}


// function call 
name()

```


7. What is the similarities between function definition and function call?

function name is same when we will define function and call the function

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid function is a object 
```

9. What is higher order function explain with an example.

when a function that accepts function definition as an argument is know as heigher order  function 

```js

function sum(add){
  return add(2,5);
}

sum(function add(a,b)  {
  return a + b;
})



```

10. Explain what is callback function. Why you can pass a function inside a function?
