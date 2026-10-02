125. Valid Palindrome

I use two pointers starting from both ends of the string. I skip non-alphanumeric characters and compare the remaining characters after converting them to lowercase. If all pairs match, the string is a palindrome. This runs in O(n) time and O(1) space.
