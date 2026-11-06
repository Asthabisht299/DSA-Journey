
# Best Time to Buy and Sell Stock

- **LeetCode Number:** 121
- **Difficulty:** Easy
- **Topics:** Array, Greedy

## Problem Description

Given an array of stock prices where prices[i] represents the price of a stock on the ith day, find the maximum profit that can be achieved by buying and selling the stock once.

The stock must be bought before it is sold.

## Example

**Input:**
prices = [7, 1, 5, 3, 6, 4]

**Output:**
5

**Explanation:**
Buy the stock at price 1 and sell it at price 6.

Maximum Profit = 6 - 1 = 5.

## Approach: Single Pass (Greedy)

1. Initialize `minPrice` with `Integer.MAX_VALUE` so that the first stock price becomes the initial minimum.
2. Initialize `maxProfit` as 0.
3. Traverse the prices array using a for loop.
4. If the current price is smaller than `minPrice`, update `minPrice`.
5. Otherwise, calculate the profit by subtracting `minPrice` from the current price.
6. If the calculated profit is greater than `maxProfit`, update `maxProfit`.
7. Return the maximum profit.

## Complexity Analysis

- **Time Complexity:** O(n) – The array is traversed only once.
- **Space Complexity:** O(1) – Only two variables are used, regardless of input size.

## Key Learning

- Array traversal
- Greedy approach
- Using `Integer.MAX_VALUE`
- Finding minimum and maximum values
- Optimizing time and space complexity

---

*Part of my Data Structures and Algorithms learning journey.*
