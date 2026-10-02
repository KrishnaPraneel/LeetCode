39. Combination Sum

I use backtracking. At each candidate, I have two choices: include it or skip it. When I include it, I stay at the same index because the problem allows using the same number multiple times. If the running sum reaches the target, I add the current combination to the result. If the sum exceeds the target or I run out of candidates, I stop exploring that path.
