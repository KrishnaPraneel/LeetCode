572. Subtree of Another Tree

I solve this using recursion. For each node in the main tree, I check whether the subtree rooted at that node is identical to subRoot. To compare two trees, I use a helper function that recursively verifies that the node values match and that both left and right subtrees are identical. If the current node doesn't match, I recursively search the left and right children. In the worst case, the time complexity is O(n × m), where n and m are the sizes of the two trees.
