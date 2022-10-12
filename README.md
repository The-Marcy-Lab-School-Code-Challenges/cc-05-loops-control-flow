# Code Challenge: Loops with Control Flow

## Instructions

1. Clone down this assignment to your `code-challenges' directory in AWS Cloud9.  
2. Code your solution using JavaScript in `index.js`. 
3. **Be sure to run and test your code throughly!**
4. By the end of Code Challenge, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on Github.

## Code Problems

1. Write a function named `greaterNum` that:
  - takes 4 arguments, both numbers.
  - returns whichever number is the greater (higher) number.
  - If two arguments are equal, it will return the string "two integers are equal"
  - If three arguments are equal, it will return the string "three integers are equal"
  - If all arguments are equal, it will return the string "all integers are equal"
  - If a given argument is not an integer data type it will return `null`
```
greaterNum(10, 7, 30, 60) //returns 60
greaterNum(1.14, 1.14, 3, 5) //returns "two integers are equal"
greaterNum(1.14, 1.14, 1.14, 5) //returns "three integers are equal"
greaterNum("21", 21, "3", 5) //returns null
```

2. Write a function named `sumOfNotDivisibleByTen` that returns the sum of all numbers 1 to (and including) 1000, that are **not**  mutiples of ten.
```
sumOfNotDivisibleByTen() //returns 450000
```


### Bonus 
3. Write a function `sortFiveNums` that takes in five integer arguments and returns the five integers sorted from greatest to least in an array. Solve this without using any sorting methods, and only using conditional statements. 
```
sortThreeNums(-14,14,-1,20) //returns [20,14,-1,-14]
sortThreeNums(2,2,50,300) //returns [300, 50, 2, 2]
```
