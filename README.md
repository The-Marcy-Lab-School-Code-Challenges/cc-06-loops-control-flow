# Code Challenge: Loops with Control Flow

## Instructions

1. Clone down this assignment to your `code-challenges' directory in AWS Cloud9.  
2. Code your solution using JavaScript in `index.js`. 
3. **Be sure to run and test your code throughly!**
4. By the end of Code Challenge, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on Github.

## Code Problems

1. Write a function named `countDoubleDigitNumbers` that takes in an integer argument that returns a **count** of the numbers that are "double digits"(multiples of 11) from  1 to (and including) the given argument. 
```js
countDoubleDigitNumbers(44) //returns 4 because 11, 22, 33, and 44 are multiples of 11 
```

2. Write a function named `sumOfNotThreeOrFive` that returns the sum of all numbers that are *not* multiples of 3 and  *not* multiples of 5 from 1 to (and including) 1000.
```js
sumOfNotThreeOrFive() //returns 266332 
// 1 + 2 + 4 + 7 + 8 + 11 + 13 + 14 + ...
```


### Bonus 
3. Write a function `multiplesOfThirty` that **returns an array** of all positive numbers from 1 to (and including) 1000 if that number is a multiple of 30. 
```js
multiplesOfThirty() // returns the following array:
/*
[
  30,  60,  90, 120, 150, 180, 210,
  240, 270, 300, 330, 360, 390, 420,
  450, 480, 510, 540, 570, 600, 630,
  660, 690, 720, 750, 780, 810, 840,
  870, 900, 930, 960, 990
]
*/
```
