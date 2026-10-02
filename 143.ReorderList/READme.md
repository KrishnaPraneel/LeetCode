143. Reorder List

I solve this in three steps. First, I use slow and fast pointers to find the middle of the list. Then I reverse the second half of the list in place. Finally, I merge the first half and the reversed second half by alternating nodes from each list. This satisfies the required ordering while using constant extra space.
