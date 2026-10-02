62. Unique Paths

I use dynamic programming. The number of ways to reach a cell is the sum of the ways to reach the cell above it and the cell to its left. Instead of storing the entire grid, I only keep one row because each row depends only on the row below it. This reduces the space complexity from O(mn) to O(n).
