# Code Challenge: Loops with Control Flow

## Instructions

1. Clone down this assignment to your `code-challenges' directory in AWS Cloud9.  
2. Code your solution using JavaScript in `index.js`. 
3. **Be sure to run and test your code throughly!**
4. By the end of Code Challenge, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on Github.

## Code Problems

1. Write a function named `allAreEqual` that:
  - takes in 3 integer arguments
  - If all arguments are equal, it will return the string "all integers are equal"
  - If two arguements are equal, it will return the string "two integers are equal"
  - If none of the arguments are equal, it will return the string "all are different"
```
allAreEqual(13, 13, 13) //returns "all integers are equal"
allAreEqual(3, 3, 5) // returns "two integers are equal"
allAreEqual(3, 5, 3) // returns "two integers are equal"
allAreEqual(3, 3, 5) // returns "two integers are equal"
allAreEqual(10, 7, 30) // returns "all are different"
```

2. Write a function named `sumOfNotDivisibleByTen` that returns the sum of all numbers 1 to (and including) 1000, that are **not** divisible by ten.
```
sumOfNotDivisibleByTen() //returns 450000
// 1 + 2 + 3 + 4 + 5 + 6 + 7 + 8 + 9 + 11 + 12 + 13 + 14 + 15 + 16 + 17 + 18 + 19 + 21 + 22...
```


### Bonus 
3. Write a function named `countMultiplesOfThree` that takes in an array of integers and returns the number of integers in the array that are multiples of three. 
```
countMultiplesOfThree([1,2,3,4,5,6,7,8,9,10]) // returns 3 because 3, 6, and 9 are multiples of three
countMultiplesOfThree([15,23,35,45,67]) // returns 2 because 15 and 45 are multiples of three
countMultiplesOfThree([2,6,14]) // returns 1 because 6 is a mutiple of three
```
