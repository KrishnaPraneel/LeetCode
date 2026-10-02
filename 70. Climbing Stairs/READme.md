70. Climbing Stairs

This is a Fibonacci-style DP problem. The number of ways to reach a step equals the sum of the ways to reach the previous two steps. Since each state depends only on the last two states, I keep two variables instead of a full DP array, resulting in O(n) time and O(1) space.
