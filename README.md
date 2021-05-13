# bitspilani-sem2-aci-assignment-1-bloxorz-game
Bloxorz game

Bloxorz Game!
Bloxorz is a 3-D block sliding puzzle game consists of a terrain that is built
by 1×1 tile with a special shape and size, and a 1×1×2 size block. This game is a
single agent path-finding problem that involves moving the block from its initial
position using four directions (right, left, up, and down) and ensuring that its ends
are always within the terrain boundary, until it falls into a 1×1 square hole in the
terrain that represents our goal state.
The block can be in three states, standing, lying horizontally, and lying
vertically. When the block reaches the hole, it must be in standing state to fall in it.
The level-1 of the game begins with the size of the terrain as 6×10 rows and
columns, starting position is at row 2 and column 2 or as user determines it, and
goal position is at row 5 and column 8.


answer the
following questions :
1) Formulate the Bloxorz problem as a search problem by depicting its states
representation, initial state, actions, transition model, goal state. [ 1M ].
  
2) Can BFS/DFS be used to solve this problem ? If so, explain how it can be
used by providing an algorithm/pseudocode [ 2M ]
  
3) Can A* search be used to solve this problem ? If so, explain how it can be
used by providing an algorithm/pseudocode [ 2M ]
  
4) Implement an agent to solve level-1 of Bloxorz game using python. [ 8M ]
  
a. You may choose to represent the game as a map using of 0,1 as shown
here. 1’s represents the tile and
0’s is void spaces & 9 represents
goal.
  
b. Show/Print the step by step
process your agent takes to reach
the goal.
  
c. You may use “X” to indicate the
current position at each step.
  
d. Also print the number of steps taken by your agent to reach the goal.
  
e. You can choose any uninformed search or informed search strategies
to implement this in python.
