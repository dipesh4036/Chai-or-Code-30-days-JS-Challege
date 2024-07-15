# Day-3 : Contorl Structure:

## Activity : 1 IF-ELSE Statement

Task : 1 Write a program to check if a number is positive , negative and zero and log the results to the console.

Task : 2 Write a program to check if a person is eligible for vote (age>=18) and log the results to the console.

```javascript
// task : 1 and 2

// task 1
const num = 34;
if (num > 0) {
    console.log(`${num} is positive`)
}
elif (num < 0) {
    console.log(`${num} is negative`)
}
else{
    console.log(`${num} is zero`)
}

// task 2
const age = 23;
if (age >= 18) {
    console.log(`${age} is eligible of vote`)
}
else{
    console.log(`${age} is not eligible of vote`)
}
```

## Activity : 2 Nested if-else Statements

Task : 3 Write a program to find the largest of three numbers using nested if-else statements.

```javascript
// task : 3
const num1 = 10;
const num2 = 20;
const num3 = 30;

if (num1 > num2) {
  if (num1 > num3) {
    console.log(`${num1} is the largest number`);
  } else {
    console.log(`${num3} is the largest number`);
  }
} else {
  if (num2 > num3) {
    console.log(`${num2} is the largest number`);
  } else {
    console.log(`${num3} is the largest number`);
  }
}
```

## Activity : 3 Switch case

Task : 4 Write a proram that uses a switch case to determine the day of the week based on a number (1-7) and log the day name to the console.

Task : 5 Write a proram that uses a swith case to assign a grade ('A','B','C','D','F') based on the score and log the grade to the console.

```javascript
// task : 4 and 5
const number = 3;
switch (number) {
  case 1:
    console.log(`${number} Monday`);
    break;
  case 2:
    console.log(`${number} Tuesday`);
    break;
  case 3:
    console.log(`${number} Wednesday`);
    break;
  case 4:
    console.log(`${number} Thursday`);
    break;
  case 5:
    console.log(`${number} Friday`);
    break;
  case 6:
    console.log(`${number} Saturday`);
    break;
  case 7:
    console.log(`${number} Sunday`);
    break;
}

// Task 5:
const score = 90;

switch (true) {
  case score >= 90:
    console.log(`A grade of ${score}`);
    break;
  case score >= 80:
    console.log(`B grade of ${score}`);
    break;
  case score >= 70:
    console.log(`C grade of ${score}`);
    break;
  case score >= 60:
    console.log(`D grade of ${score}`);
    break;
  case score < 60:
    console.log(`F grade of ${score}`);
    break;
  default:
    console.log(`Invalid score: ${score}`);
}
```

## Activity : 4 Conditional (Ternary) Operator:

Task : 6 Write a program that uses the ternary operator to check if a number is even or odd and log the result to the console.

```javascript
// Task : 6
// Task : 6
const num = 4;
const result = num % 2 === 0 ? "number is even" : "number is odd";
console.log(result);
```

## Activity : 5 Combining Conditional

Task : 7 Write a program to check if a year is a leap year using multiple condition (divsible by 4 ,but not 100 unless also divisible by 400) and log the result to the console.

```javascript
// Task : 5
const year = 2006;

if ((year % 4 === 0 && year % 100 !== 0) || year % 400 === 0) {
  console.log(`${year} is a leap year`);
} else {
  console.log(`${year} is not a leap year`);
}
```

## Achievement:

• Implement and understand basic if-else control flow.

• Use nested if-else statements to handle multiple conditions.

• Utilize switch cases for control flow based on specific values.

• Apply the ternary operator for concise condition checking.

. Combine multiple conditions to solve more complex problems.
