191. Number of 1 Bits

I use the bit manipulation trick n & (n - 1), which removes the rightmost set bit. I repeatedly apply it and count the number of iterations until n becomes zero. The count represents the number of 1 bits. The algorithm runs in O(k) time and O(1) space.
