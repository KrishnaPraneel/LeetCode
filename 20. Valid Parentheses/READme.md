20. Valid Parentheses

I use a stack to track opening brackets. For every closing bracket, I verify that it matches the most recent opening bracket on the stack. If a mismatch occurs, I return false. At the end, the stack must be empty. This runs in O(n) time and O(n) space.
