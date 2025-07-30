# Leetcode-2419-Longest-Subarray-With-Maximum-Bitwise

------------------------------
🌟 Intuition:
-------------------------------
When you perform a bitwise AND over a subarray, the result is always less than or equal to the smallest number in that subarray.
So, to get the **maximum AND**, every number in the subarray must be the **maximum number** in the entire array.

That means:
- First, find the maximum value in the array.
- Then, find the longest contiguous subarray where every element equals that maximum.

Only those subarrays will produce the highest AND result.

-------------------------------
🧠 Example:
-------------------------------
Input: nums = [1, 3, 3, 2, 3]
Max element = 3
Valid subarrays: [3, 3] and [3]
Longest one = [3, 3] → length = 2

-------------------------------
✅ Time & Space Complexity:
-------------------------------
Time: O(n)
Space: O(1)
*/
