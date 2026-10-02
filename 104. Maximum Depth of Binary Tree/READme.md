104. Maximum Depth of Binary Tree

I use recursive DFS. For each node, the maximum depth is one plus the maximum depth of its left and right subtrees. The base case returns zero for a null node. This visits every node once, giving O(n) time and O(h) space complexity.
