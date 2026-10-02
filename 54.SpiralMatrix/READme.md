54. Spiral Matrix

I maintain four boundaries: top, bottom, left, and right. I traverse the outer layer of the matrix in four directions and then move the corresponding boundary inward. After each layer, I check whether the boundaries have crossed. Since every element is visited exactly once, the algorithm runs in O(m × n) time and uses O(1) extra space excluding the output.
