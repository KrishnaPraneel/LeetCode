139. Word Break

I use bottom-up DP. dp[i] tells me whether the substring starting at i can be segmented. For each position, I try all dictionary words and check if they match the current substring. If a match leads to a valid suffix, I mark dp[i] as true. The answer is dp[0]
