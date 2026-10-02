121. Best Time to Buy and Sell Stock

I scan the array once while maintaining the lowest stock price seen so far. For each day, I compute the profit from selling at the current price and update the maximum profit. If I encounter a lower price, I update the buy price. This gives O(n) time and O(1) space complexity.
