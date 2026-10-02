98. Validate Binary Search Tree

I perform a DFS while carrying valid lower and upper bounds for each node. Every node must satisfy lower < node.val < upper. The bounds are updated as I traverse left and right. If any node violates its range, I return false. This runs in O(n) time and O(h) space.
