322. Coin Change

I use bottom-up dynamic programming. dp[a] stores the minimum number of coins needed to make amount a. I initialize all amounts as unreachable and set dp[0] = 0. For each amount, I try every coin and update the answer using 1 + dp[a - coin]. The final answer is stored in dp[amount]; if it remains unreachable, I return -1.
