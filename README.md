# Tic-tac-toe-minmax-
Tic-tac-toe seems dumb, but it actually requires you to lookahead one opponent's move to ensure that you will not loss. That is, you need to consider your opponent's move after your next move.

For example, suppose that the computer uses 'O'. At (D), the computer did not consider the opponent's next move and place at the corner (which is preferred over the side). At (E), the opponent was able to block the computer's winning move and create a fork.

 X |   |       X |   |       X |   |       X |   |       X |   | X
-----------   -----------   -----------   -----------   -----------
   |   |         | O |         | O |         | O |         | O |
-----------   -----------   -----------   -----------   -----------
   |   |         |   |         |   | X     O |   | X     O |   | X
    (A)           (B)           (C)           (D)           (E)
