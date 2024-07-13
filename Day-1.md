# Day-1 : Variable and Data Types:

## Activity : 1 Variable Declarations

Task : 1 Declare a variable using **var** , assign it a number, and log the value to the console.

Task : 2 Declare a variable using **let** , assign it a string, and log the value to the console.

```javascript
// task : 1
var num = 23;
console.log(num);

// task : 2
let str = "Hello";
console.log(str);
```

## Activity : 2 Constant Declarations

Task : 3 Declare a variable using **const** , assign it a boolean, and log the value to the console.

```javascript
// task : 3
const bool = true;
console.log(bool);
```

## Activity : 3 Data Types

Task : 3 Create Variable of different data type (number, string, boolean,object,array) and log each variable type using the **typeof** operator.

```javascript
// task : 4
const num = 23;
console.log(typeof num);

const string = "hello world";
console.log(typeof string);

const array = [1, 2, 3, 4, 5];
console.log(typeof array);

const boolean = true;
console.log(typeof boolean);

const object = { id: 01, name: "XYZ", email: "XYZ@example.com" };
console.log(typeof object);
```

## Activity : 4 Reassigning Variable

Task : 4 Declare Variable using **let**,assign it an initial value,reassign a new value , and log both values to the console.

```javascript
// Task : 4
let str = "Hello";
console.log(str);
str = "World!";
console.log(str);
```

## Activity : 5 Understanding Const

Task : 5 Try reassigning variable declaration with **const** and observe the error.

```javascript
// Task : 5
const num = 4;
num = 6;
// This will cause an error since you cannot reassign a value to a constant variable.
```

## Achievement:

Know how to declare variables using var, let, and const.
Understand the different data types in JavaScript.
Be able to use the typeof operator to identify the data type of a variable.
Understand the concept of variable reassignment and the immutability of const variables.
