1. What does thread of execution means in JavaScript?
```js
//Thread of execution is the sequence in which the codes gets exectued in javascript.
```
2. Where the JavaScript code gets executed?
```js
//All the javascript codes get executed in javascript engine.
```
3. What does context means in Global Execution Context?
```js
//Context means environment in which codes get executed
```
4. When do you create a global execution context.
```js 
//Global execution context get created automatically by javascript engine whenever it is running out code for the first time.
```
5. Execution context consists of what all things?
```js
//It consist of two parts : one where we store data , variables etcc and other where we execute our codes
```
6. What are the different types of execution context?
```js
// the different types of exection context are:Global execution context and  function execution context.
```
7. When global and function execution context gets created?
```js
//Global execution context get created automatically by javascript engine whenever it is running out code for the first time whereas function execution context is created when we execute any function.
```
8. Function execution gets created during function execution or while declaring a function.
```js 
//It gets created white execution of a function .
```
9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

![./img/gec1.jpg]

![](./img/image-name.jpg)



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
![./img/gec2.jpg]


![](./img/image-name.jpg)



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
![./img/gec3.jpg]
