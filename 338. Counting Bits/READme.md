338. Counting Bits

I use dynamic programming. For each number i, I find the largest power of two less than or equal to it, called offset. The number of set bits in i is 1 + dp[i - offset] because removing the leading power-of-two bit leaves a smaller number whose bit count is already known. This gives O(n) time and O(n) space complexity.
