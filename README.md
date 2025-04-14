/**
 * Problem: Trapping Rain Water (LeetCode #42)
 * 
 * Description:
 * Given an array of non-negative integers representing an elevation map
 * where the width of each bar is 1, compute how much water it can trap after raining.
 * 
 * Approach:
 * - Precompute left max and right max for each index
 * - For each index, trapped water = min(left max, right max) - height
 * 
 * Time Complexity: O(n)
 * Space Complexity: O(n)
 * 

 */
