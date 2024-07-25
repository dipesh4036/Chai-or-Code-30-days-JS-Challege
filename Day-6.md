# Day-6 : Arrays:

## Activity : 1 Array creation and access

Task : 1 Write a array of numbers from 1 to 5 and log the array to the console.

Task : 2 Access the first and last elements of the array and log them to the console.

```javascript
// task : 1 and 2

// Task 1
const array = [1, 2, 3, 4, 5];
console.log(array);
// Task 2

console.log(array[0]);
console.log(array[4]);
```

## Activity : 2 Array Methods (Basic)

Task : 3 Use the **PUSH** method to add a new number to the end of the array and log the updated array.

Task : 4 Use the **POP** method to remove the last element from the array and log the updated array.

Task : 5 Use the **SHIFT** method to remove the first element from the array and log the updated array.

Task : 6 Use the **UNSHIFT** method to add a new number to the beginning of the array and log the updated array.

```javascript
// task : 3
const arr = [1, 2, 3, 4];
arr.push(5);
console.log(arr);
// Task : 4
arr.pop();
console.log(arr);
// Task : 5
arr.shift();
console.log(arr);
// Task : 6
arr.unshift(0); // Adding 0 to the beginning of the array
console.log(arr);
```

## Activity 3 : Array Methods (intermediate)

Task : 7 Use the **MAP** method to create a new arraay where each number is doubled and log thw new array.

Task : 8 Use the **FILTER** method to create a new array with only even numbers and log the new array.

Task : 9 Use the **REDUCE** method to calculate the sum of all numbers in the array and log the result.

```javascript
// task : 7
const numbers = [1, 2, 3, 4, 5];
const result1 = numbers.map((values) => values * 2);
console.log(result1);
// Task : 8
const number = [1, 2, 3, 4, 5];
const result2 = number.filter((values) => values % 2 == 0);
console.log(result2);
// Task : 9
const num = [1, 2, 3, 4, 5];
const result3 = num.reduce((acc, val) => acc + val, 0);
console.log(result3);
```

## Activity : 4 Arraty Iteration:

Task : 10 Use a **FOR** loop to iterate over the array and log each element to the console.

Task : 11 Use the **FOREACH** methos to iterate over the array and log each element to the console

```javascript
// Task : 10
const arr1 = [1, 2, 3, 4, 5];
for (let i = 0; i < arr1.length; i++) {
  console.log(arr1[i]);
}
// Task : 11
const arr2 = [1, 2, 3, 4, 5];
arr2.forEach((value) => console.log(value));
```

## Activity : 5 Multi-deimination Array:

Task : 12 Creaet a two dimensional array (matrix) and log the entire array to the console.

Task : 13 Access and log a specified element from the two-dimensional array.

```javascript
// Task : 12
const twoD = [
  [1, 2, 3],
  [4, 5, 6],
];
console.log(twoD);

// Task :13
console.log(towD[0][1]);
```

## Achievement:

• Create and manipulate array using various methods.

• Transform and aggregate array data using map, filter and reduce.
• Iterate over arrays using loops and iteatiion methods.

• Understand and work with multi-dimensional arrays.
