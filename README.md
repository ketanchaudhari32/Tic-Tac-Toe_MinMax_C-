# Tic-Tac-Toe_MinMax_CPP

Min-max algorithm is a recursive or backtracking algorithm which is used in decision-making and game theory. It provides an optimal move for the player assuming that opponent is also playing optimally.    
    
Goal of algorithm is that the human player gets the minimum benefit while AI get the maximum benefit.

The minimax algorithm performs a depth-first search algorithm for the exploration of the complete game tree.
    
The minimax algorithm proceeds all the way down to the terminal node of the tree, then backtrack the tree as the recursion.

Sample Output:
```
-------------------------------------------------------------------

Tic-Tac-Toe
Human vs AI

-------------------------------------------------------------------

Do you want to start first?(y/n) : n

Choose a cell numbered from 1 to 9 as below and play

                         1 | 2 | 3 
                        -----------
                         4 | 5 | 6 
                        -----------
                         7 | 8 | 9 

COMPUTER has put a O in cell 1

                         O |   |   
                        -----------
                           |   |   
                        -----------
                           |   |   

You can insert in the following positions : 2 3 4 5 6 7 8 9 

Enter the position = 4

HUMAN has put a X in cell 4

                         O |   |   
                        -----------
                         X |   |   
                        -----------
                           |   |   

COMPUTER has put a O in cell 2

                         O | O |   
                        -----------
                         X |   |   
                        -----------
                           |   |   

You can insert in the following positions : 3 5 6 7 8 9 

Enter the position = 3

HUMAN has put a X in cell 3

                         O | O | X 
                        -----------
                         X |   |   
                        -----------
                           |   |   

COMPUTER has put a O in cell 5

                         O | O | X 
                        -----------
                         X | O |   
                        -----------
                           |   |   

You can insert in the following positions : 6 7 8 9 

Enter the position = 8

HUMAN has put a X in cell 8

                         O | O | X 
                        -----------
                         X | O |   
                        -----------
                           | X |   

COMPUTER has put a O in cell 9

                         O | O | X 
                        -----------
                         X | O |   
                        -----------
                           | X | O 

COMPUTER has won

quit(y/n) : y
```