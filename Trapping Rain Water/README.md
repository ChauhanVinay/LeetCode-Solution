
Trapping Rain Water

Problem Description:
Given an array height representing the height of bars, where the width of each bar is 1, compute how much rainwater can be trapped after raining.

Approach:
The solution utilizes a two-pointer approach to track the left and right boundaries of the current container. It iterates through the array, adjusting the boundaries based on the maximum height encountered so far on each side. The trapped water is calculated by subtracting the height of the current position from the maximum height of the boundary.

Steps:
Initialize variables to track the left (l) and right (r) pointers, and maximum heights (lmax and rmax).
Iterate through the array using the two pointers l and r.
Update the maximum height encountered on each side.
If the current maximum height on the left side is less than the right side, move the left pointer and calculate trapped water.
Otherwise, move the right pointer and calculate trapped water.
Repeat until the left pointer is less than the right pointer.
Return the total trapped water.

Time Complexity:
The time complexity of this solution is O(n), where n is the length of the input array height, as it iterates through the array once.

Space Complexity:
The space complexity is O(1) since the algorithm uses only a constant amount of extra space regardless of the input size.