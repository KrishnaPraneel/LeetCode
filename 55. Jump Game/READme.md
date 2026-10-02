55. Jump Game

I used a greedy approach. I start from the last index and treat it as my goal. Then I iterate backwards through the array. If the current index can reach the goal (i + nums[i] >= goal), I update the goal to the current index. By the end, if the goal has moved back to index 0, it means I can reach the last index from the start. This works because I'm continuously finding the leftmost position that can eventually reach the end.
