# N_puzzle_generator

Usage: python dim complexity
Example: python n_puzzle_gen.py 3 3

Return will be a 3*3 puzzle like: 1,4,2,3,5,0,6,7,8

N_puzzle problem:

1 0 
2 3      
      to 
0 1
2 3
      
However, not all combinations of numbers are solvable for a n_puzzle because of its moving rule.
For example,

2 0
1 3      
      to 
0 1
2 3

which is unsolvable.

Here are some ready examples:

7,0,4,2,3,6,8,5,1

--IDA*--
[7, 0, 4]

[2, 3, 6]

[8, 5, 1]

MAX FRINGE SIZE:     61
MAX STACK DEPTH:     22
STACK DEPTH:         22
NODES EXPANDED:      76
RUNNING TIME:        17.078876 ms 
MEMORY USAGE :       20480 bytes 
COST OF PATH :       21 
PATH :               ['DOWN', 'LEFT', 'UP', 'RIGHT', 'DOWN', 'RIGHT', 'DOWN', 'LEFT', 'LEFT', 'UP', 'RIGHT', 'RIGHT', 'UP', 'LEFT', 'DOWN', 'RIGHT', 'DOWN', 'LEFT', 'LEFT', 'UP', 'UP'] 

2,15,4,7,1,11,6,3,5,13,0,9,14,12,8,10
[2, 15, 4, 7]
[1, 11, 6, 3]
[5, 13, 0, 9]
[14, 12, 8, 10]
--IDA*--
MAX FRINGE SIZE:     94009
MAX STACK DEPTH:     47
STACK DEPTH:         47
NODES EXPANDED:      93997
RUNNING TIME:        59850.682020 ms 
MEMORY USAGE :       22896640 bytes 
COST OF PATH :       46 
PATH :               ['UP', 'LEFT', 'UP', 'RIGHT', 'DOWN', 'LEFT', 'DOWN', 'RIGHT', 'UP', 'UP', 'RIGHT', 'DOWN', 'LEFT', 'LEFT', 'UP', 'LEFT', 'DOWN', 'RIGHT', 'DOWN', 'DOWN', 'RIGHT', 'UP', 'UP', 'UP', 'LEFT', 'LEFT', 'DOWN', 'DOWN', 'RIGHT', 'DOWN', 'LEFT', 'UP', 'RIGHT', 'RIGHT', 'RIGHT', 'DOWN', 'LEFT', 'LEFT', 'UP', 'RIGHT', 'RIGHT', 'UP', 'LEFT', 'LEFT', 'LEFT', 'UP'] 

Therefore, this work guarrantees you will get a sovable n_puzzle.

Enjoy.
