
Remove Duplicates from Sorted Array


Problem Description:
Given a sorted array nums, remove the duplicates in-place such that each element appears only once and returns the new length. Do not allocate extra space for another array; you must do this by modifying the input array in-place with O(1) extra memory.

Approach:
The provided solution utilizes a two-pointer approach to remove duplicates in-place. It iterates through the array, comparing adjacent elements. If a duplicate is found, it skips over it by moving the pointer j forward.

Steps:
Initialize a pointer j to track the current position of the non-duplicate elements.
Iterate through the array nums.
Compare the current element nums[i] with the element at nums[j].
If they are different, increment j and copy nums[i] to nums[j].
Continue this process until the end of the array.
Return the length of the array with duplicates removed, which is j + 1.

Time Complexity:
The time complexity of this solution is O(n), where n is the length of the input array nums, as it iterates through the array once.

Space Complexity:
The space complexity is O(1) since the algorithm modifies the input array in-place without using any additional space.

