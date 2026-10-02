3. Longest Substring Without Repeating Characters
 
I use a sliding window with two pointers. The window always contains unique characters. I expand the window using the right pointer, and whenever a duplicate is found, I shrink the window from the left until the duplicate is removed. At each step, I update the maximum window length. Since each character is added and removed at most once, the time complexity is O(n) and the space complexity is O(n).
