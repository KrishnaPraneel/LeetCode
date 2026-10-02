91. Decode Ways

At each position, I can either decode one digit or, if valid, two digits. I use dynamic programming where dp[i] stores the number of ways to decode the substring starting at index i. I compute the values from right to left and combine the counts from the valid one-digit and two-digit choices. This gives an O(n) time solution.
