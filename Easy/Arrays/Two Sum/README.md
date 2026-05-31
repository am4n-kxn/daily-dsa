# Two Sum

## Problem
Given an array of integers `nums` and an integer `target`,
return indices of the two numbers such that they add up to `target`.

## Approach
USed a two pointer method to compare sum of every elemnt and the elemnts after it, after traversing the array once the first pointer is incremented by one and so on until the whole array is complted / target is found

For each element:
1. Calculate sum with next element.
2. Return indexes if sum = target, move ahead by one if sum isn't the target
3. after reaching the end, move the left pointer by one

## Complexity
Time: O(n^2)
Space: O(1)

## Platform
LeetCode 