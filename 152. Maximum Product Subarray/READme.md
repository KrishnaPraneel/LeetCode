152. Maximum Product Subarray

I use dynamic programming with two running values: the maximum and minimum product ending at the current index. I need both because multiplying by a negative number can turn a large negative product into the maximum positive product. For each element, I update the current maximum and minimum products and keep track of the global maximum. This runs in O(n) time and O(1) space.
