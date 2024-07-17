# Day-5 : Function:

## Activity : 1 Function Declaration

Task : 1 Write a function to check is a number is even or odd and log the result to the console.

Task : 2 Write a function to calculate the square of a number and log the result to the console.

```javascript
// task : 1 and 2

// Task 1
function checknum(number) {
  if (number % 2 === 0) console.log(`${number} is even`);
  else console.log(`${number} is odd`);
}
checknum(5);

// Task 2
function square(number) {
  result = number * number;
  console.log(result);
}
square(5);
```

## Activity : 2 Function Expression

Task : 3 Write a function expression to find the maximum of two numbers and log the result to the console.

Task : 4 Write a function expression to concatenate two stings and log the result to the console.

```javascript
// task : 3
const max = function (number1, number2) {
  if (number1 > number2) console.log(number1);
  else console.log(number2);
};
max(3, 4);
// Task : 4
const concatenate = function (str1, str2) {
  const result = str1 + str2;
  console.log(result);
};
concatenate("XY", "ZA");
```

## Activity : Arrow Functions

Task : 5 Write a arrow function to calculate the sun of two numbers and return the result.

Task : 6 Write a arrow function to ccheck if a string contains a specific character and retrun a boolean value.

```javascript
// task : 5
const sum = (num1, num2) => {
  const result = num1 + num2;
  return result;
};
console.log(sum(4, 5));
// Task 6:
const checker = (str, char) => {
  return str.includes(char);
};
console.log(checker("dipesh", "a"));
```

## Activity : 4 Function Parameters and Default Values:

Task : 7 Write a function that takes two parameters and returns their product.Provide a default value for thw second parameter.

Task : 8 Write a function that takes a person's name and age and returns a greeting message. Provide a default value for the age.


```javascript
// Task : 7
const product = (num1, num2 = 1) => {
  return num1 * num2;
}

console.log(product(5));      
console.log(product(5, 3));   

// Task :8
const greet = (name, age = 30) => {
  return `Hello, ${name}! You are ${age} years old.`;
}

console.log(greet('Alice'));       
console.log(greet('Bob', 25)); 
```

## Activity : 5 Higher-Order Function:

Task : 9 Write a higher-order function that takes a number and calls the function that many times.

Task : 10 Write a higher-order function that takes a two function and a value , applies the first function to the value , and then appplies the second function to the result.

```javascript
// Task : 9
const callNTimes = (number, func) => {
  for (let i = 0; i < number; i++) {
    func();
  }
}
// Example usage: calling a function 3 times
callNTimes(3, () => {
  console.log("Function called");
});

// Task 10:
const applyFunctions = (func1, func2, value) => {
  const result1 = func1(value);
  const result2 = func2(result1);
  return result2;
}

// Example usage: applying two functions to a value
const addOne = (x) => x + 1;
const double = (x) => x * 2;

const finalResult = applyFunctions(addOne, double, 3);
console.log(finalResult);  // Outputs: 8 (adds 1 to 3, then doubles the result)

```

## Achievement:

• Understand and define functions using function declarations, expressions, and arrow function

• Use function parameters and default values effectively.

• Create and utilize higher-order functions.

• Apply functions to solve common problems and perform calculations.

• Enhance code reusability and organization using functions.