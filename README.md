#Day18ofMyLeetCodeJourney – Problem 167: Two Sum II - Input Array Is Sorted
🔍 This classic problem gets a twist—because the array is already sorted, we can ditch brute force and go for something smarter.

📘 Problem Summary:
Given a 1-indexed, sorted array, return the indices of the two numbers that add up to a given target.

🎯 Constraints:
Use constant extra space
Return 1-based indices
Only one valid solution exists

💡 Approach:
✅ Two Pointer Technique
Place one pointer at the start and the other at the end.
Move pointers inward based on sum:
If sum is too big → move right pointer left
If sum is too small → move left pointer right
If sum matches → return indices (+1 for 1-based indexing)

🧠 This works because the array is sorted – the key optimization.

🧪 Example:
Input:
 numbers = [2, 7, 11, 15], target = 9
 Output:
 [1, 2]
 (2 + 7 = 9)

🧠 Learning:
This problem taught me how sorted data allows for elegant solutions using two-pointer logic, saving both time and space.
A small twist in the input condition can lead to a big change in the optimal approach. 🧩
