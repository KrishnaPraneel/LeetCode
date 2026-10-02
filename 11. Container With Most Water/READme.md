11. Container With Most Water

I start with pointers at both ends of the array. At each step, I compute the area and move the pointer with the smaller height inward, since the smaller height limits the container. This greedy two-pointer strategy finds the maximum area in O(n) time and O(1) space.
