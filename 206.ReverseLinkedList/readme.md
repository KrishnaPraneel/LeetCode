206. Reverse Linked List
I use an iterative approach with three pointers: prev, curr, and next.
* curr points to the current node I'm processing.
* prev points to the already reversed portion of the list.
* Before changing any pointers, I store curr.next in next so I don't lose access to the rest of the list.
Then for each node:
1. Save the next node.
2. Reverse the current node's pointer (curr.next = prev).
3. Move prev and curr one step forward.
When curr becomes None, I've reached the end of the list, and prev points to the new head of the reversed list.
