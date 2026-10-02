56. Merge Intervals

I first sort the intervals by start time. Then I iterate through them and compare each interval with the last merged interval. If the current interval starts before or at the end of the last merged interval, they overlap, so I merge them by extending the end time. Otherwise, I add the current interval as a new interval. Since sorting takes O(n log n) and the scan is O(n), the overall complexity is O(n log n).
