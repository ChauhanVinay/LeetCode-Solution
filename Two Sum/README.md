
Two Sum Problem in an arrays

Problem Description:

Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target. You may assume that each input would have exactly one solution, and you may not use the same element twice. You can return the answer in any order.

Approach:
The provided solution uses a brute-force approach, iterating through the array and checking all possible pairs of numbers to see if their sum equals the target.

Steps:
Iterate through the array nums.
For each element nums[i], iterate through the remaining elements starting from nums[i+1].
Check if the sum of the current element and any other element equals the target.
If found, return the indices of the two numbers as an array.
If no such pair is found, return null.

Time Complexity:
The time complexity of this solution is O(n^2), where n is the length of the input array nums.

Space Complexity:
The space complexity is O(1) since only a constant amount of extra space is used for storing the indices.