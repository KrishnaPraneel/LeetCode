268.Missing Number

Since the array contains all numbers from 0 to n except one, I can compute the expected sum of 0 through n and subtract the actual array sum. 
The difference is the missing number. This runs in O(n) time and O(1) space. Another optimal approach uses XOR, where equal numbers cancel out, 
leaving only the missing value.
