
# Contains Duplicate

- **LeetCode Number:** 217
- **Difficulty:** Easy
- **Topics:** Array, Hash Table

## Problem Description

Given an integer array, return true if any value appears at least twice in the array. Return false if every element is distinct.

## Example 1

**Input:**
nums = [1, 2, 3, 1]

**Output:**
true

**Explanation:**
The number 1 appears more than once in the array.

## Example 2

**Input:**
nums = [1, 2, 3, 4]

**Output:**
false

**Explanation:**
All elements are distinct.

## Approach: HashSet

1. Create a HashSet to store unique elements.
2. Traverse the array using an enhanced for loop.
3. Check whether the current element already exists in the HashSet using `contains()`.
4. If the element exists, return `true` because a duplicate is found.
5. Otherwise, add the element to the HashSet using `add()`.
6. If the loop completes without finding duplicates, return `false`.

## Complexity Analysis

- **Time Complexity:** O(n) – Each element is processed once on average, with O(1) average HashSet operations.
- **Space Complexity:** O(n) – The HashSet may store all elements if there are no duplicates.

## Key Learning

- HashSet in Java
- Duplicate detection
- `contains()` and `add()` methods
- Enhanced for loop
- Time and space complexity analysis

---


