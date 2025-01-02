---
title: HW 22 - Recursion
due_date: 2025-1-3
---

Save your files here: ```.../APCSA_1/apcsa-assignments-YourUsername/homework/22_recursion/RecursiveFunctions.java```

## Exercise 1: Sum digits

Write the solution to the following problem:

Given a non-negative int n, return the sum of its digits recursively (no loops). Do not use strings to solve the problem. Example: 12945 -> 1 + 2 + 9 + 4 + 5 = 21

Hints:

How to get the digit at the end 12945 => 5?

How to remove the last digit 12945 => 1294?

These questions will guide you in finding the solution:

- What is the base case?
- Which operations can break up the numbers into a single digit and the rest? 
- What is the recursive case?


## Exercise 2: Fibonacci Sequence

The sequence follows the rule that each number is equal to the sum of the preceding two numbers (0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, 233 … )

![image](https://github.com/user-attachments/assets/fe3e4340-2415-44a5-84c1-7e08f168f88d)

These questions will guide you in finding the solution:

- What is the recursive case? 
- When do you call the recursive case?
- What is(are) the base case(s)?
  
When you test your fibonacci method:

1. Check how long it takes to run the method. Run this command in your terminal: time java Fibonacci.java
   
2. What is the largest number such that fibonacci(number) fits in an int? (does not overflow)
