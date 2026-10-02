53. Maximum Subarray

I use Kadane's Algorithm. I maintain a running sum of the current subarray. If the running sum becomes negative, I reset it to zero because a negative prefix would only reduce the sum of any future subarray. At each step, I update the maximum sum seen so far. This gives an O(n) solution.
