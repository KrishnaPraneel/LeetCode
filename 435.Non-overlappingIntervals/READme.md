435. Non-overlapping Intervals

I sort the intervals by their ending times. Then I greedily keep intervals that do not overlap with the last selected interval. If an interval overlaps, I remove it because the interval with the earlier ending time is already being kept, which leaves the most room for future intervals. This gives the minimum number of removals. The time complexity is O(n log n) due to sorting, and the scan itself is O(n).
