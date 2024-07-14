# Day-2 : Operators:

## Activity : 1 Arithmetic Operators

Task : 1 Write a program to add two numbers ans log the result to the console.

Task : 2 Write a program to subtract two numbers ans log the result to the console.

Task : 3 Write a program to multiplt two numbers ans log the result to the console.

Task : 4 Write a program to divide two numbers ans log the result to the console.

Task : 5 Write a program to find the remainder when one number is divided by anothe and log the result to the console.

```javascript
// task : 1 to 4

const num1 = 10;
const num2 = 20;

console.log(num1 + num2); // 30
console.log(num1 - num2); // -10
console.log(num1 * num2); // 200
console.log(num1 / num2); //0.5
console.log(num1 % num2); // 10
```

## Activity : 2 Assignment Operators

Task : 6 Use the += operator to add a number to a variable and log the result to te console.

Task : 7 Use the -= operator to subtact a number from a variable and log the result to te console.

```javascript
// task : 6
const num1 = 10;
let result1 = 0; // Initialize result1 to 0 (or any other starting value)
result1 += num1;
console.log(result1); // This will now output 10 (0 + 10)

const num1 = 10;
let result1 = 20; // Initialize result1 with a starting value (here, 20)
result1 -= num1;
console.log(result1); // This will now output 10 (20 - 10)
```

## Activity : 3 Comparison Operators

Task : 8 Write a proram to compare two numbers using > and **<** and **>**log the result to the console.

Task : 9 Write a proram to compare two numbers using > and **<=** and **>=**log the result to the console.

Task : 10 Write a proram to compare two numbers using > and **==** and **===**log the result to the console.

```javascript
// task : 4
const num1 = 10;
const num2 = 20;
result1 = num1 > num2;
console.log(result1);

result2 = num1 < num2;
console.log(result2);

result3 = num1 >= num2;
console.log(result3);

result4 = num1 <= num2;
console.log(result4);

result5 = num1 == num2;
console.log(result5);

result6 = num1 === num2;
console.log(result6);
```

## Activity : 4 Logical Operations

Task : 11 Write a program that uses the && operator to combine two conditions and log the result to the console.

Task : 12 Write a program that uses the || operator to combine two conditions and log the result to the console.

Task : 13 Write a program that uses the ! operator to negate a conditions and log the result to the console.

```javascript
// Task : 4
const bool1 = true;
const bool2 = false;
result1 = bool1 && bool2;
result2 = bool1 || bool2;
result3 = !bool1;

console.log(result1);
console.log(result2);
console.log(result3);
```

## Activity : 5 Ternary Operator

Task : 14 Write a program that uses the ternary operator to check if a number is positive or negative and log the result to the console.

```javascript
// Task : 5
const num = 45;

const result = num > 0 ? "positive" : "negative";
console.log(result);
```

## Achievement:

• Understand and use arithmetic operators to perform basic calculations.

• Use assignment operators to modify variable values.

• Compare values using comparison operators.

• Combine conditions using logical operators.

• Use the ternary operator for concise conditional expressions.
