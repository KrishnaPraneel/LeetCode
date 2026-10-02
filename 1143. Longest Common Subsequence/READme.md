1143. Longest Common Subsequence

I use dynamic programming. dp[i][j] represents the length of the longest common subsequence between the suffixes text1[i:] and text2[j:]. If the characters match, I take 1 + dp[i+1][j+1]. Otherwise, I try skipping a character from either string and take the maximum. I fill the table bottom-up and return dp[0][0].
