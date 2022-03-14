# Jumping-Tiles

Consider a game of "jumping tiles" where there is a linear set of contiguous tiles separated by various distances. Your goal is to jump from the starting tile to the end tile in this certain fashion:

You can only jump forward, not backward
You have to jump through all the tiles
You start with a "jumping strength" k that denotes the maximum number of tiles you can skip
When you skip exactly k tiles in a move, your "jumping strength" will decrease by 1

Your goal is to find the minimum k needed to reach the end tile given the distances. The tiles are always sorted in increasing numerical value and the end tile number can be less than 1 million.
