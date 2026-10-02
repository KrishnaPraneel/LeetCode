300. Longest Increasing Subsequence

I use dynamic programming where LIS[i] stores the length of the longest increasing subsequence starting at index i. I process the array from right to left. For each position, I check all elements to its right. If a larger element exists, I can extend the subsequence and update LIS[i] with 1 + LIS[j]. The answer is the maximum value in the DP array.
