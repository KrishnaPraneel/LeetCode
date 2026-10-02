235. Lowest Common Ancestor of a Binary Search Tree

Since this is a Binary Search Tree, I can use its ordering property. Starting from the root, if both target nodes are smaller than the current node, I move left. If both are larger, I move right. Otherwise, I've found the split point where one node is on each side, or one of the nodes is the current node itself. That split point is the Lowest Common Ancestor.
