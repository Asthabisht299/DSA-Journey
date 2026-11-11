# Reverse String

- **LeetCode Number:** 344
- **Difficulty:** Easy
- **Topics:** String, Two Pointers

## Problem Statement

Write a function that reverses a string.

The input string is given as an array of characters `s`.

You must reverse the string in-place with O(1) extra memory.

## Example 1

**Input:** `s = ["h","e","l","l","o"]`

**Output:** `["o","l","l","e","h"]`

## Example 2

**Input:** `s = ["H","a","n","n","a","h"]`

**Output:** `["h","a","n","n","a","H"]`

## Approach: Two Pointers

1. Initialize two pointers: `left` at index 0 and `right` at the last index.
2. Run a while loop while `left < right`.
3. Store the character at the left pointer in a temporary variable.
4. Swap the characters at the left and right positions.
5. Increment the left pointer and decrement the right pointer.
6. Repeat until the pointers meet or cross.

## Complexity Analysis

- **Time Complexity:** O(n) – Each character is visited at most once.
- **Space Complexity:** O(1) – Reversal is performed in-place using only a temporary variable.

## Key Learning

- Two Pointer Technique
- In-place array manipulation
- Character swapping
- While loop
- Time and space complexity

---

