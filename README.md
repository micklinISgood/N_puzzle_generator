# N_puzzle_generator

Usage: python dim complexity

            python n_puzzle_gen.py 3 3

Return will be a 3*3 puzzle like: 1,2,5,3,4,8,6,7,0

N_puzzle problem:

            1 0         to          0 1
            2 3                     2 3

      
However, not all combinations of numbers are solvable for a n_puzzle because of its moving rule.
For example,

            2 0         to          0 1
            1 3                     2 3


which is unsolvable.

Therefore, this work guarrantees you a sovable n_puzzle.

Enjoy.

Here is a handy example:

1,2,5,3,4,8,6,7,0

--IDA*--

            [1, 2, 5]
            [3, 4, 8]
            [6, 7, 0]

MAX FRINGE SIZE:     1

MAX STACK DEPTH:     5

STACK DEPTH:         5

NODES EXPANDED:      4

RUNNING TIME:        2.820015 ms 

MEMORY USAGE :       20480 bytes 

COST OF PATH :       4 

PATH :               ['UP', 'UP', 'LEFT', 'LEFT'] 
