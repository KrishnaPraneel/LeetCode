19. Remove Nth Node From End of List

I use two pointers with a gap of n nodes. After moving the right pointer n steps ahead, I move both pointers together until the right pointer reaches the end. The left pointer then points to the node before the one that needs to be removed. This solution runs in O(n) time and O(1) space.
