Building Reinforcement Learning Agent and Environment for Numerical Tic-Tac-Toe.

Instead of X’s and O’s, the numbers 1 to 9 are used. In the 3x3 grid, numbers 1 to 9 are filled, with one number in each cell. The first player plays with the odd numbers, the second player plays with the even numbers, i.e. player 1 can enter only an odd number in the cell while player 2 can enter an even number in one of the remaining cells. Each number can be used exactly once in the entire grid. The player who puts down 15 points in a line - (column, row or a diagonal) wins the game.

Rules of the Game:
1. The game will be played on a 3x3 grid (9 cells) using numbers from 1 to 9. Each number can be used exactly once in the entire grid.
2. There are two players: one is the Reinforcement Learning (RL) agent and other is the environment.
3.The RL agent is given odd numbers {1, 3, 5, 7, 9} and the environment is given the even numbers {2, 4, 6, 8}
4. Each of them takes a turn. The player with odd numbers always goes first.
5. At each round, a player puts one unused number on a blank spot.
6. The objective is to make 15 points in a row, column or a diagonal. The player can use the opponent's numbers in the grid to make 15.
7. The game terminates when any one of the players makes 15.
