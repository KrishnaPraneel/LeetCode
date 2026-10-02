57. Insert Interval

Since the intervals are already sorted, I scan them once. For each interval, either it comes completely before the new interval, completely after it, or overlaps with it. If it overlaps, I merge by updating the start and end of newInterval. Once I find an interval that starts after the merged interval ends, I insert the merged interval and append the remaining intervals. This gives an O(n) solution.
