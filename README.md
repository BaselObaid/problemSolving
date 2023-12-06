# Problem Solving

This repository contains my solutions to various problems on LeetCode, implemented in Java.

## Table of Contents

- [Minimum Absolute Difference](#minimum-absolute-difference)
- [Largest Perimeter Triangle](#largest-perimeter-triangle)
- [Array Pair Sum](#array-pair-sum)
- [eliminate maximum number of monsters](#eliminate-maximum-number-of-monsters)

## Minimum Absolute Difference

**Problem Description:**

[Minimum Absolute Difference on LeetCode](https://leetcode.com/problems/minimum-absolute-difference/)

**Submission:**

- [LeetCode Submission](https://leetcode.com/submissions/detail/1112204293/)

**Explanation:**

I used the following approach:

1. Sort the array to simplify finding the minimum absolute difference.
2. Iterate through the sorted array and find pairs with the minimum absolute difference.
3. Add the pairs to the result list.

**Complexity Analysis:**

- Time Complexity: O(n log n) - due to sorting.
- Space Complexity: O(1) - constant space for variables.

Feel free to explore the code and provide any feedback or improvements!

## Largest Perimeter Triangle

**Problem Description:**

[Largest Perimeter Triangle on LeetCode](https://leetcode.com/problems/largest-perimeter-triangle/)

**Submissions:**
- [LeetCode Submission 1](https://leetcode.com/problems/largest-perimeter-triangle/submissions/1112231761)
- [LeetCode Submission 2](https://leetcode.com/problems/largest-perimeter-triangle/submissions/1112251938)


**Explanation:**
1. **Solution 1:**
I used the following approach:

   - Sort the array to easily identify the longest sides of potential triangles.
   - Iterate through the sorted array and check if the current three elements satisfy the triangle inequality.
   - If true, calculate the perimeter and update the largest perimeter if the current perimeter is larger.
  
2. **Solution 2:**
It is better than the prev approach 
   - An alternative approach using a backward iteration through the sorted array.
   - Check if the sum of the two smaller sides is greater than the longest side.
   - If true, return the perimeter; otherwise, return 0.
     
**Complexity Analysis:**
for the two solutions 
- Time Complexity: O(n log n) - due to sorting.
- Space Complexity: O(1) - constant space for variables.

## Array Pair Sum

**Problem Description:**

[Array Pair Sum on LeetCode](https://leetcode.com/problems/array-partition/)

**Submission:**

- [LeetCode Submission](https://leetcode.com/problems/array-partition/submissions/1112353785)

**Explanation:**

I used the following approach:

1. Sort the array in non-decreasing order to pair adjacent elements effectively.
2. Iterate through the sorted array, and add every alternate element starting from the first element (index 0).
3. The sum of the odd-indexed elements represents the maximized sum.

**Complexity Analysis:**

- Time Complexity: O(n log n) - due to sorting.
- Space Complexity: O(1) - constant space for variables.

# eliminate maximum number of monsters

**Problem Description:**

[Eliminate Maximum on LeetCode](https://leetcode.com/problems/eliminate-maximum-number-of-monsters/)

**Submission:**

- [LeetCode Submission](https://leetcode.com/problems/eliminate-maximum-number-of-monsters/submissions/1113899261)

**Explanation:**

I used the following approach:

1. Calculate the time required for each monster to reach the city.
2. Sort the array of time values in ascending order.
3. Iterate through the sorted array and find the first monster that cannot be eliminated before reaching the city.
4. Return the count of monsters that can be eliminated before this point.

**Complexity Analysis:**

- Time Complexity: O(n log n) - due to sorting.
- Space Complexity: O(1) - constant space for variables.



