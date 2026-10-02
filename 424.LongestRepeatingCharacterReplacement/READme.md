424. Longest Repeating Character Replacement

The most frequent character in the window is the one I keep. All other characters need to be replaced. If the number of replacements needed (window size - maxFreq) exceeds k, I shrink the window. Otherwise, I expand it and update the answer. This gives an O(n) sliding-window solution.
