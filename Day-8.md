# Day-8 : ES6+ Featues:

## Activity : 1 Template Literals

Task : 1 Use template literals to creact a string that includes variables for a person's name and age and log the string to the console.

Task : 2 Create a multi-line string using template literals and log it to the console.

```javascript
// task : 1 and 2

// Task 1
// Task 1
const name = "XYZ";
const age = 22;
const string = `Person's name is ${name} and age is ${age}.`;
console.log(string);

// Task 2
// Task 2
const str = `
This is my paragraph.
My paragraph name is "newpara".
The paragraph is quite long.
`;
console.log(str);
```

## Activity : 2 Destructuring

Task : 3 Use array destructuring to extract the first and second elements from an arary of numbers and log them to the console.

Task : 4 Use object destructuring to extact the title and author from a book object and log them to the console.

```javascript
// task : 3
const [first, second] = [1, 2, 3, 4];
console.log(first);
console.log(second);
// Task : 4
const { title, author } = {
  title: "somthing",
  author: "XYZ",
};
console.log(title);
console.log(author);
```

## Activity 3 : Spread and Rest Operations

Task : 5 Use the spread operator to create a new array that includes all elements of an existing array plue additional elements and log the new array to the console.

Task : 6 Use the rest opertor in a function to accept an arbitrry number of arguments, sum them,and return the result.

```javascript
// task : 5
const arr1 = [1, 2, 3, 4];
const arr2 = [...arr1, 5, 6, 7];
console.log(arr1);
console.log(arr2);


// Task : 6
function sum(...arr) {
  return arr.reduce((acc, num) => acc + num, 0);
}

const result = sum([1, 2, 3, 4, 5, 6, 7, 8, 9, 10]);
console.log(result);
```

## Activity : 4 Default parameters:

Task : 7 Write a function that takes two parameters and returns their product,with the second parameter having a default value of 1. log the result of calling this function with and without the second parameter.

```javascript
// Task : 7
function product(num1, num2=1){
  return num1*num2;
}

product(4,5)
product(4);
```

## Activity : 5 Enhanced Object Literals:

Task : 8 Use enhanced object literals to creact an object with mathod and properties,and log the object to the console.

Task : 9 Create an objectwith computed names based on variables and log the object to the console.

```javascript
// Task : 8
const calculator = {
  operand1: 0,
  operand2: 0,
  setOperands(num1, num2) {
    this.operand1 = num1;
    this.operand2 = num2;
  },
  add() {
    return this.operand1 + this.operand2;
  },
  subtract() {
    return this.operand1 - this.operand2;
  }
};
console.log(calculator);

// Task : 9
const keyPrefix = 'key';
const obj = {
  [`${keyPrefix}1`]: 'value1',
  [`${keyPrefix}2`]: 'value2',
  [`${keyPrefix}3`]: 'value3'
};

console.log(obj);

```

## Achievement:

• Understand and use template literals for string interpolation and multi-line strings.

• Apply destructuring to extract values from arrays and objects.

• Utilize spread and rest operators for array manipulation and function arguments.

• Define functions with default parameters.

• Create objects using enhanced object literals, including methods and computed property names.
