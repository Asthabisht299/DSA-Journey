
# Two Sum

- **LeetCode Number:** 1
- **Difficulty:** Easy
- **Topic:** Arrays, HashMap

## Problem

Given an array of integers and a target, return the indices of two numbers whose sum equals the target.

## Example

**Input:**
nums = [2, 7, 11, 15]
target = 9

**Output:**
[0, 1]

**Explanation:**
nums[0] + nums[1] = 2 + 7 = 9.

## Approach: HashMap

1. Create a HashMap to store numbers and their indices.
2. Traverse the array using a loop.
3. Calculate the remaining number needed to reach the target.
4. Check whether that number already exists in the HashMap.
5. If it exists, return both indices.
6. Otherwise, store the current number and its index.

## Complexity Analysis

- **Time Complexity:** O(n)
- **Space Complexity:** O(n)

## Key Learning

- Understanding HashMap in Java.
- Using containsKey() and put().
- Solving the Two Sum problem efficiently.
