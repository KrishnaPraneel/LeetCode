200. Number of Islands

I use Depth-First Search (DFS) to find and mark all connected land cells. I iterate through every cell in the grid, and whenever I encounter a '1', I've found a new island, so I increment the island count. Then I run DFS from that cell to visit all adjacent land cells (up, down, left, and right), marking them as '0' so they won't be counted again. This ensures each island is counted exactly once.
