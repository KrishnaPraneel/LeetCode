347. Top K Frequent Elements

I first count the frequency of every number using a hash map. Then I create buckets where the index represents the frequency and each bucket stores numbers that occur that many times. Finally, I iterate from the highest frequency bucket to the lowest and collect elements until I have k results. This avoids sorting and achieves O(n) time complexity.
