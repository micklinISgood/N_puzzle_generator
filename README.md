# N_puzzle_generator

Usage: python dim complexity

Example: python n_puzzle_gen.py 3 3

Return will be a 3*3 puzzle like: 7,0,4,2,3,6,8,5,1

N_puzzle problem:

            1 0         to          0 1
            2 3                     2 3

      
However, not all combinations of numbers are solvable for a n_puzzle because of its moving rule.
For example,

            2 0         to          0 1
            1 3                     2 3


which is unsolvable.

Therefore, this work guarrantees you will get a sovable n_puzzle.

Enjoy.

Here is a ready example:

7,0,4,2,3,6,8,5,1

--IDA*--

            7, 0, 4
            2, 3, 6
            8, 5, 1

MAX FRINGE SIZE:     61

MAX STACK DEPTH:     22

STACK DEPTH:         22

NODES EXPANDED:      76

RUNNING TIME:        17.078876 ms

MEMORY USAGE :       20480 bytes

COST OF PATH :       21 

PATH :               ['DOWN', 'LEFT', 'UP', 'RIGHT', 'DOWN', 'RIGHT', 'DOWN', 'LEFT', 'LEFT', 'UP', 'RIGHT', 'RIGHT', 'UP', 'LEFT', 'DOWN', 'RIGHT', 'DOWN', 'LEFT', 'LEFT', 'UP', 'UP']
