100. Same Tree

I recursively compare corresponding nodes in both trees. If both nodes are null, they match. If one is null or the values differ, the trees are different. Otherwise, I recursively compare the left and right subtrees. This runs in O(n) time and O(h) space due to the recursion stack.
