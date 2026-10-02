153. Find Minimum in Rotated Sorted Array

Since the array was originally sorted and then rotated, it consists of two sorted portions. I use binary search to determine which half contains the rotation point. If the left half is sorted, then the minimum must be in the right half. Otherwise, the minimum lies in the left half. I keep track of the smallest value seen and shrink the search space until I find the minimum. This gives O(log n) time complexity.
