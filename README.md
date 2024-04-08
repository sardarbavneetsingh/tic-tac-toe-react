# A tic-tac-toe game that:

- Lets you play tic-tac-toe,
- Indicates when a player has won the game,
- Stores a game’s history as a game progresses,
- Allows players to review a game’s history and see previous versions of a game’s board.

## Brief

The tutorial covers building a Tic-Tac-Toe game using React. It starts by having the Square component manage its own state, then refactors to lift the state up to the parent Board component. This allows the Board to pass props down to the Square components and handle the game logic centrally. 

The tutorial then adds functionality to declare a winner, display the current player's turn, and prevent moves in occupied squares. Finally, it introduces "time travel" by storing the full history of moves in the top-level Game component, allowing the user to navigate through previous game states. 

*Source: [Tutorial: Tic-Tac-Toe](https://react.dev/learn/tutorial-tic-tac-toe)*
