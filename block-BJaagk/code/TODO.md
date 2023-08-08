1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

let percent = function percentage(marks, total) {
  return (marks * 100) / total;
}
let percent = function(marks, total) {
  return (marks * 100) / total;
}

let percentage = (marks, total) => {
  return (marks * 100) / total;
}

let percentage = (marks, total) => (marks * 100) / total;
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
//Answer
Function Declaration
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
Function Expression
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
Function Expression
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
Function Expression
```

```js
let percentage = (marks, total) => (marks * 100) / total;
Function Expression
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
```js
example:
let square = function(side) {
  return `side * side`;
}
```
4. Why is a function call an expression in JavaScript?
```js
//A function call is an expression that includes the name of the function being called or the value of a function pointer and, optionally, the arguments being passed to the function.
a function call always returns a value i.e it is an expression.
```
5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // valid 5
five = add; // valid
five = five(10, 11); //valid 21
five = function () {
  return 'Hello';
}; // invalid
```

6. What is the difference between function definition and function call? Explain with an example.
```js
function add() //declaration

add() //call
```
7. What is the similarities between function definition and function call?
```js
//function declaration is an expression(function is an object)
//function call is an expression(function always returns a value)
```
8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid
```

9. What is higher order function explain with an example.
```js 
//A function that accepts other function as an argument is called higher order function for example:
function createQuote(quote , callBback){
  var myQuote = "An apple a day," + quote;                                                                
  callBback(myQuote)
}

function completeQuote(quote){
  console.log(quote)
}

createQuote("keeps a Dr. away!" , completeQuote)
```
10. Explain what is callback function. Why you can pass a function inside a function?
```js 
//Callback function is that function which is passed as an argument inside another function.
We can pass function inside a function because function is an object and i can be passed as an argument inside another function.
```