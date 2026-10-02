230. Kth Smallest Element in a BST

Since this is a Binary Search Tree, an inorder traversal visits the nodes in ascending sorted order. Instead of storing all values, I perform an iterative inorder traversal using a stack.
I first keep going left and push nodes onto the stack. When I can no longer go left, I pop a node from the stack, which gives me the next smallest element. Each time I visit a node, I decrement k. When k reaches zero, I've found the k-th smallest element and return its value. After visiting a node, I move to its right subtree and continue the inorder traversal.
