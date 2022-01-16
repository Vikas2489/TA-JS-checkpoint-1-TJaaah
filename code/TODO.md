1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}
 


// second
function sum(a, b) {
  console.log(a + b);
}

 let first = sum(a,b);

```

```js
 So, here in the first function there is a return statement which will always return a value. Whenever a function a has a return statement it means that it will always return a single value. While in the second function, there is no return statement then it will show undefined in the output. When we will execute this function then it will console the sum of a and b.
```

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

```js
value of first will be depended on the arguments which will be passed.
value of second will be undefined.
```

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

```js

Sum function will only add a and b as written in the return statment. Third parameter will be ignored. 

```

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

```js
Yes we can store the first `sum` function in a variable named `add` because function are objects and objects is value that can be stored in a variable.
```
5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

function sayHello(name){
  return `hello ${name}`;
}

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```

The output of the above code will be this 'Hello, John'. Because, as username is defined outside the function then in it will access the username from outside.


7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // this will alert only userName which 'John'

showMessage(); // The output of the above code will be this 'Hello, John'.

alert(userName); // this will alert only userName which 'John'
```

8. What is a Anonymous Function give example of three functions.

```js

Anonymous function is function which  we can directly write a function assign it to a variable.
 
 for example :- let add = function(a,b){
   return a+b;
 }

 let multiply = function(a,b){
   return a*b;
 }


let substract = function(a,b){
   return a-b;
 }
````

9. Can function declaration be a Anonymous Function? Explain

```js

function declaration can be a anonymous function because while declaring or defining a function we can directly store that function  
into a variable.

```


10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```

```js

userName
calculateBMI
fullName
addOrConcat
sumOfOdd

```