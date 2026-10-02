647. Palindromic Substrings

I use the expand-around-center technique. Every palindrome has either a single-character center or a two-character center. For each index, I expand outward from both centers while the characters match. Each successful expansion corresponds to one palindromic substring, so I increment the count. Since there are O(n) centers and each expansion can take O(n), the overall time complexity is O(n²) with O(1) extra space.
