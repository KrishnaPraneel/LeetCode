141. Linked List Cycle

I use Floyd's Cycle Detection algorithm with two pointers. The slow pointer moves one node at a time and the fast pointer moves two nodes at a time. If the linked list contains a cycle, the fast pointer will eventually meet the slow pointer. If there is no cycle, the fast pointer will reach the end of the list. This gives O(n) time complexity and O(1) extra space.
