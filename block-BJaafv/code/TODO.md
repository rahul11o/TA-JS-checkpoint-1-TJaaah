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
```
// In the first function there is a return statement but in second function there is no return statement.

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

// Since the first function has return statement and is stored in a varible named first , so the value of variable first will be result of operation a + b, but the value of variable second will be undefined.

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

//The output will be 36 (12 + 24), the function will not consider third parameter because while definig the function we have mentioned only two parameter which is a and b.


4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
yes , we can store it. its because there is return statement, infact any function having return statement can be stored in the variables.

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
```js
function sayHello(name){
return `Hello + " " + name`;
}
```
6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
// "hello, john"

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // "john"

showMessage(); // "Hello, john"

alert(userName); // "john"
```

8. What is a Anonymous Function give example of three functions.

9. Can function declaration be a Anonymous Function? Explain

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.
// 1)findCrtOpt
// 2)addTwoNum 
// 3)showMessage
// 4)chooseYesOrNo 
// 5)declarePassorFail

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
