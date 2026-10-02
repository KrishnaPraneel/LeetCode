33. Search in Rotated Sorted Array

At each step, one half of the rotated array is guaranteed to be sorted. I first determine whether the left or right half is sorted. Then I check if the target lies within the sorted half's range. If it does, I search that half; otherwise, I search the other half. Since I eliminate half of the search space each iteration, the time complexity is O(log n).
