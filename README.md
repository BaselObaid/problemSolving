# Problem Solving

This repository contains my solutions to various problems on LeetCode, implemented in Java.

## Table of Contents

- [Minimum Absolute Difference](#minimum-absolute-difference)
- [Largest Perimeter Triangle](#largest-perimeter-triangle)

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

**Submission:**
- [LeetCode Submission](https://leetcode.com/problems/largest-perimeter-triangle/submissions/1112231761/)

**Explanation:**

I used the following approach:

1. Sort the array to easily identify the longest sides of potential triangles.
2. Iterate through the sorted array and check if the current three elements satisfy the triangle inequality.
3. If true, calculate the perimeter and update the largest perimeter if the current perimeter is larger.

**Complexity Analysis:**

- Time Complexity: O(n log n) - due to sorting.
- Space Complexity: O(1) - constant space for variables.


