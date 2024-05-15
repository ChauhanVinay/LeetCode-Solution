Search in Rotated Sorted Array

Problem Description:
Given a rotated sorted array nums and an integer target, return the index of target in the array. If target is not found, return -1.

Approach:
The provided solution employs a linear search approach. It iterates through the array nums, checking each element to see if it matches the target value.

Steps:
Iterate through the array nums.
For each element, compare it with the target value.
If the element matches the target, return its index.
If no match is found after iterating through the entire array, return -1.

Time Complexity:
The time complexity of this solution is O(n), where n is the length of the input array nums, as it iterates through the array once in the worst case.

Space Complexity:
The space complexity is O(1) since the algorithm uses only a constant amount of extra space regardless of the input size.

