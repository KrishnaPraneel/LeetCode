238. Product of Array Except Self

For each index, the answer is the product of all numbers to its left multiplied by the product of all numbers to its right. I first store prefix products in the result array. Then I traverse from right to left while maintaining a postfix product and multiply it into the result. This avoids division and uses O(1) extra space apart from the output array.
