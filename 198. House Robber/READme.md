198. House Robber

I use dynamic programming. At each house, I decide whether it's better to rob the current house or skip it. If I rob it, I add its value to the best result from two houses back. If I skip it, I keep the best result from the previous house. Since each decision only depends on the previous two states, I optimize the DP to O(1) space by storing only two variables.
