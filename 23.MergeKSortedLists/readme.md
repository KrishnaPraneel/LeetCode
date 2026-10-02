23. Merge k Sorted Lists

I solve this using divide and conquer. I repeatedly merge pairs of sorted linked lists, similar to the merge step in merge sort. Each round halves the number of lists, and there are O(log k) rounds. Since every node is processed once per round, the total time complexity is O(N log k), where N is the total number of nodes across all lists. This is more efficient than repeatedly merging into a single list one at a time.
