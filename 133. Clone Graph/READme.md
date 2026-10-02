133. Clone Graph

Since the graph may contain cycles, I use DFS with a hash map that stores the mapping from original nodes to cloned nodes. When I visit a node, I first check whether it has already been cloned. If so, I return the existing clone. Otherwise, I create a new node, store it in the map, recursively clone all neighbors, and connect them to the cloned node. This ensures every node isd exactly once and avoids infinite recursion caused by cycles. The time complexity is O(V + E) and the space complexity is O(V).
