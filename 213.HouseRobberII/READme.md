213. House Robber II

Because the houses are arranged in a circle, I can't rob both the first and last house. So I split the problem into two linear House Robber problems: one excluding the first house and one excluding the last house. I solve each using the standard O(1) space DP solution and return the larger result. This gives O(n) time complexity.
