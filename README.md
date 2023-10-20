# Chess Game

Welcome to the Chess Game! This is a console-based chess game implemented in Python. Play chess, a classic board game that tests your strategic thinking and tactical skills. This game allows you to challenge your friends or practice your chess strategies against an AI opponent.

## Features

- Play chess against a friend or a computer AI.
- Customizable AI difficulty levels.
- Interactive command-line interface.
- Legal move validation and error handling.
- Support for castling, en passant, pawn promotion, and more.
- Save and load game state.

## Requirements

- Python 3.6 or higher

## Installation

1. Clone the repository:

    ```shell
    git clone https://github.com/yourusername/chess-game.git
    cd chess-game
    ```

2. Run the game:

    ```shell
    python chess.py
    ```

3. Follow the on-screen instructions to start a new game, load a saved game, or adjust AI difficulty.

## Usage

- Start the game, either in 2-player mode (Player vs. Player) or against the AI (Player vs. AI).
- Make your moves using algebraic notation (e.g., "e2 to e4").
- The game will guide you through the rules and valid moves.
- Save and load your game progress for later.

## Gameplay
Our Chess Game follows the standard rules of chess. Here's a brief overview: 
- Moving Pieces: Click on a piece to select it, and then click on the square you want to move it to. Legal moves will be highlighted.
- Castling: To castle, move the king two squares toward the rook you want to castle with, and the rook will automatically move to the square next to the king.
- En Passant: En passant captures are supported. If your opponent's pawn moves two squares forward, you can capture it as if it had only moved one square.
- Pawn Promotion: When a pawn reaches the opposite end of the board, you can choose to promote it to a queen, rook, bishop, or knight.
- Check and Checkmate: The game will detect when your king is in check and when it is checkmated.
- Stalemate: The game will also recognize a stalemate or a draw by repetition.
- Draw by Fifty-Move Rule: The game will declare a draw if no captures or pawn moves occur for 50 consecutive moves.

## Contributing

Contributions are welcome! If you'd like to contribute to this Chess Game project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add a new feature'`
4. Push to your branch: `git push origin feature-name`
5. Open a pull request.

Please make sure to follow the [Code of Conduct](CODE_OF_CONDUCT.md).

## License

This Chess Game is open-source software and is available under the [MIT License](LICENSE). Feel free to use, modify, and distribute it as you like.

Happy gaming!
