48. Rotate Image

To rotate the matrix 90 degrees clockwise in-place, I first transpose the matrix, which converts rows into columns by swapping matrix[r][c] with matrix[c][r]. Then I reverse every row. The combination of transpose and row reversal produces the desired clockwise rotation without using extra space.
