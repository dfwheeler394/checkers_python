
Save/Resume game
It's possible to save the game and resume playing at a later date.


Specific Features of Game:

- Move Validation:
  Checker's ordinary moves are enforced by the game, including:
    - User can only move his own pieces
    - User can only move to available squares
    - User can only move piece one space diagonally
    - User must take any available jump

  - Time Keeping
    - Enforced by datetime module

  - Conditions for Winning and Losing
    - User wins when all opposing pieces are off the board
    - User loses when there are no available moves
    - User loses if time runs out or if user resigns the game

  - Save/Resume game
    - It's possible to save game to disk, using JSON
