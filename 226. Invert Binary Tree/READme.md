226. Invert Binary Tree

I use DFS recursion. For each node, I swap its left and right child pointers, then recursively invert the left and right subtrees. Since every node is visited exactly once, the time complexity is O(n). The extra space comes from the recursion stack, which is O(h), where h is the height of the tree.
