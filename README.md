# Day30-50-days-coding-challenge

## Problem 1: Diameter of a Binary Tree

- Goal: Find the length of the longest path between any two nodes in a binary tree.
- Approach: Use DFS to compute depths of subtrees and update the global maximum diameter.
- Time Complexity: O(N), where N is the number of nodes.
- Space Complexity: O(h), where h is the height of the tree.

Example:
Input: root = [1,2,3,4,5]
Output: 3

## Problem 2: Find the Duplicate Number

- Goal: Find the duplicate integer in the array without modifying the array and using constant extra space.
- Approach: Floyd’s Tortoise and Hare (Cycle Detection) algorithm.
- Time Complexity: O(n)
- Space Complexity: O(1)
- Edge cases: All elements are the same, large arrays, smallest possible n.

Example:
Input: nums = [1,3,4,2,2]
Output: 2

This solution is part of the #DrGViswanathanChallenge for 50 days of coding.

Stay tuned for Day 31!
