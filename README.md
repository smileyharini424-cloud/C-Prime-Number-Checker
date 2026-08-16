# C Prime Number Checker

## Explanation

This program checks whether a given positive integer is a prime number.

A prime number has exactly two factors: 1 and itself.

Examples:

2, 3, 5, 7, 11, 13

## Problem Statement

Write a C program to determine whether a given positive integer is a prime number.

## Features

- Accepts a positive integer
- Checks whether the number is prime
- Uses a for loop
- Uses divisibility checking
- Stops checking when a divisor is found
- Handles numbers less than 2

## How It Works

The program first checks whether the number is less than 2.

Numbers less than 2 are not prime.

For other numbers, the program checks possible divisors starting from 2.

The loop only checks up to the square root of the number.

If the number is divisible by any value in this range, it is not prime.

If no divisor is found, the number is prime.

## Technologies Used

- C
- GCC Compiler
- Code Editor

## Data Structure Used

No data structure is used.

## Methods Used

- main()
- printf()
- scanf()

## Control Structures Used

- for loop
- if else statement
- break statement

## Operators Used

- %
- ==
- <=
- /
- ++

## Program Flow

Start
↓
Read number
↓
Check number < 2
↓
If true → Not Prime
↓
Otherwise start checking divisors
↓
Check divisibility
↓
If divisor found → Not Prime
↓
If no divisor found → Prime
↓
Display result
↓
End

## Sample Input

Enter a positive integer: 29

## Sample Output

29 is a prime number.

## Sample Input 2

Enter a positive integer: 20

## Sample Output 2

20 is not a prime number.

## Time Complexity

O(√n)

## Space Complexity

O(1)

## Key Learning

This program teaches how to check divisibility efficiently and introduces the concept of prime numbers.

## File Location

prime.c

## Repository Structure

C-Prime-Number-Checker/
├── README.md
└── prime.c

## Author

V.Harini
