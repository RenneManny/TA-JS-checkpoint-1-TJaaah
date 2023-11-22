1. Using loops take 10 inputs from user and find the average of all the numbers.

2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}//error
```

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
  ```js
  function getEvenSum(max){
            let sum=0;
            for(let i=1;i<=max;i++){
                if(i%2===0){
                    sum+=i;
                }
            }
            return sum;
        }
        let result=getEvenSum(10);
        console.log(result);
        ```
4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
```js
  function getEvenSum(max){
            let sum=0;
            for(let i=1;i<=max;i++){
                if(i%2!==0){
                    sum+=i;
                }
            }
            return sum;
        }
        let result=getEvenSum(10);
        console.log(result);
        ```
// 5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

// - If the input value is less than 0 return `not a valid input`
// - For example if the input is `123` output should be `6`.

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // output
check(1); // output
check(5); // output
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // You are Arya
getOutput('John'); // You are John
getOutput(); // Who are you
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya')
  if (name === 'John') 
  return 'Who are you';
}

getOutput('Arya'); //undefined
getOutput('John'); //undefined
getOutput(); // undefined
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
Yes function can have multiple return statements while using if else clause.or when using loops etc.
10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
for loop:
in for loop  the variable initialization takes place ,then condition is check and after that the value is incremented or decremented.
syntax:
for(let i=0;i<10;i++>){
  ///code goes here
}
while loop:
in while loop first the variable is declared, then condition is checked and if the condition is true the iteration takes place.
synatx:
let i=0;
while(i<=10>){
//code goes here
}
i++;
usage:-For loop is used if we already knows the number of iteration .
While loop is used when we don't know the number of iterations.