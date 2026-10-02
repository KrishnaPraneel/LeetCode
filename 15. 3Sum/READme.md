15. 3Sum
    
I first sort the array so I can use the two-pointer technique. Then I fix one number at a time and search for two other numbers that sum to its negative. Since the array is sorted, if the current sum is too small I move the left pointer right, and if it's too large I move the right pointer left. Whenever I find a valid triplet, I add it to the result and skip duplicates to avoid repeated answers. The overall time complexity is O(n²), which is much better than the O(n³) brute-force approach.
