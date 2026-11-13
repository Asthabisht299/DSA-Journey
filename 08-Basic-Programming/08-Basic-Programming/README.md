# Check Prime Number

- **Problem Number:** 2
- **Difficulty:** Easy
- **Topics:** Math, Loops, Conditional Statements

## Problem Statement

Write a Java program to check whether a given number is a prime number.

A prime number is a number greater than 1 that has exactly two factors: 1 and itself.

## Example 1

**Input:** `n = 7`

**Output:** `Prime`

**Explanation:** 7 is divisible only by 1 and 7.

## Example 2

**Input:** `n = 9`

**Output:** `Not Prime`

**Explanation:** 9 is divisible by 1, 3 and 9.

## Approach

1. Check whether the number is less than or equal to 1. If yes, it is not prime.
2. Run a loop starting from 2.
3. Check whether the number is divisible by any value in the loop using the modulus operator `%`.
4. If the remainder is 0, the number is not prime.
5. If no divisor is found, the number is prime.

## Complexity Analysis

- **Time Complexity:** O(√n) – An optimized solution checks divisors only up to the square root of the number.
- **Space Complexity:** O(1) – Only a fixed number of variables are used.

## Key Learning

- Prime numbers
- Modulus operator (`%`)
- For loop
- If-else conditions
- Time and space complexity

---

*Part of my Data Structures and Algorithms learning journey.*
