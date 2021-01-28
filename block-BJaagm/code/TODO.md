1. What does thread of execution means in JavaScript?
when javascript engine execute the code line by line is called thread of execution

2. Where the JavaScript code gets executed?
Javascript code gets executed inside global execution context

3. What does context means in Global Execution Context?
context means environment in which you are execute the code 

4. When do you create a global execution context.
whenever the javascript engine run your code then create first exicution context  

5. Execution context consists of what all things?


6. What are the different types of execution context?
global and function execution context

7. When global and function execution context gets created?
globle execution context is the first exicution context that created by javascript engine whenever running your code for the first time but 

function execution create whenever we execute the function 

8. Function execution gets created during function execution or while declaring a function.
when call the function that time create function execution

9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

`![](./imgs/ans1)`



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

`![](./img/ans2)`



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

`![](./imgs/ans3.jpg)`