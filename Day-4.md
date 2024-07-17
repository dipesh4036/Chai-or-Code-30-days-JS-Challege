# Day-4 : Loops:

## Activity : 1 For loop

Task : 1 Write a program to print number from 1 to 10 using for loop.

Task : 2 Write a program to print the multiplication table of 5 using a for loop.

```javascript
// task : 1 and 2

// task 1
for (let i = 1;i<=10:i++){
  console.log(i);
}
// task 2
const n = 5;
for(let = 1;i<=10;i++){
  console.log(`${n} X ${i} = ${n*i}`);
}
```

## Activity : 2 While Loop

Task : 3 Write a program to calculate the sum of numbers from 1 to 10 using a while loop.

Task : 4 Write a program to print numbers from 10 to 1 using a while loop.

```javascript
// task : 3
const sum = 0;
const i = 1;
while (i <= 10) {
  sum += i;
  i++;
}
console.log(sum);

// Task : 4
const i = 10;
while (i > 0) {
  console.log(i);
  i--;
}
```

## Activity : 3 Do While loop

Task : 4 Write a proram to print number from 1 to 5 using a do while loop.

Task : 5 Write a proram to calculate the factorial of a number using a do while loop

```javascript
// task : 4 and 5
const i = 1;
do {
  console.log(i);
  i++;
}while(i<=5)

// Task 5:
const fact = 1;
cosnt n = 5;
const j = 1
do{
  fact = fact*j;
  i++;
}while(j<=n);
console.log(fact);
```

## Activity : 4 Nested Loops:

Task : 6 Write a program to print a pattern using nested for loops.

-
- -

---

---

---

```javascript
// Task : 6
for (let i = 0; i <= 5; i++) {
  for (let j = 0; j < i; j++) {
    console.log("*");
  }
  console.log(" ");
}
```

## Activity : 5 Loop Control Statements:

Task : 7 Write a program to print numbers from 1 to 10 ,but skip the number 5 using the **continue** statement.

Task : 8 Write a program to print numbers from 1 to 10 ,but stop the loop when rhe number is 7 using the **break** statement.

```javascript
// Task : 5
for (let i = 1; i <= 10; i++) {
  if (i == 5) {
    continue;
  }
  console.log(i);
}

// Task 6:
for (let i = 1; i <= 10; i++) {
  if (i == 7) {
    break;
  }
  console.log(i);
}
```

## Achievement:

• Understand and use for loops to iterate over a sequence of numbers.

• Utilize while loops for iteration based on a condition.

• Apply do...while loops to ensure the loop body is executed at least once.

• Implement nested loops to solve more complex problems.

• Use loop control statements (break and continue) to control the flow of loops
