5. Longest Palindromic Substring

A palindrome is symmetric around its center. Every palindrome has either one center character (odd length) or two center characters (even length). For each index, I treat it as a center and expand outward while the left and right characters match. During expansion, I track the longest palindrome found. Since there are O(n) centers and each expansion can take O(n), the time complexity is O(n²) and the space complexity is O(1).
