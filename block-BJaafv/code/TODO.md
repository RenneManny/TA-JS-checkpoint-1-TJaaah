<!-- 1. What is the difference between the two `sum` function given below? -->

```js
// first
function sum(a, b) {
  let first= a + b;
  return first;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```
```In the first function the function will return the value i.e sum of a and b but in second function the function will not return a vakue instead of it it will log a value in the console.```
 <!-- 2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`. -->
<!-- In the first function the function will return the value i.e sum of a and b but in second function the function will not return a vakue instead of it it will log a value in the console. -->
```In the first function the function will return the value i.e sum of a and b but in second function the function will  return a value undefined and it will log a value in the console.```
<!-- 3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why? -->
```It will add only two arguments i.e first two arguments and the third argument will not be passed because we haven't defined the parameter for this.```
<!-- 4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why? -->
```Yes i can store the function in a variable because in js functions are values and variables are used to store values.```
<!-- 5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`. -->
```js
function sayHello(name) {
    return `hello ${name}`;
}
sayHello("Arya");
```


<!-- 6. What will be the output of the function below and why? --> -->

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
``The output of the above code will be `hello john` because here we have assigned the value JOHN to username variable .Even if we are not providing the argument it will fetch the value of the userName variable. ``
<!-- 7. What will be the output for `Output1` `Output2` and `Output3` in the code below. -->

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // John

showMessage(); // undefined because we have not passed the argument yet.

alert(userName); // John
```

<!-- 8. What is a Anonymous Function give example of three functions. -->

<!-- 9. Can function declaration be a Anonymous Function? Explain -->
```Function declaration can be annonymous function because annonymous function is just a function without any specific name.```
<!-- 10. Give 5 example of good naming convention for defining a function. You can read the details below to do that. -->

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
