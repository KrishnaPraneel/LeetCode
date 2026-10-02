73. Set Matrix Zeroes

I make two passes through the matrix. First, I store all rows and columns containing a zero in two sets. Then I make a second pass and zero out any cell whose row or column is marked. The solution runs in O(mn) time and uses O(m + n) extra space.
