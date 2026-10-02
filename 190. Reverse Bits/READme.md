190. Reverse Bits

I process the integer one bit at a time. I extract the least significant bit using n & 1, place it into the corresponding reversed position in the result, and then shift the input right. Since there are always 32 bits, the algorithm runs in O(1) time and O(1) space.
