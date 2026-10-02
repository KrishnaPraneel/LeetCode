128. Longest Consecutive Sequence
     
I use a hash set for O(1) lookups. The key optimization is that I only start counting a sequence if the current number is the beginning of that sequence, meaning n - 1 is not present in the set. Then I expand forward and count consecutive numbers. This ensures every number is visited at most once across all sequences, giving O(n) time complexity.
