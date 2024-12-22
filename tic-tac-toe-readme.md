# Tic Tac Toe Game

A modern, graphical implementation of the classic Tic Tac Toe game using Python and Tkinter. Features a sleek dark theme interface with color-coded players and comprehensive game tracking.

![Tic Tac Toe Game Screenshot](placeholder-for-screenshot.png)

## Features

- 🎮 Clean, modern dark theme interface
- 🎯 Color-coded X's (red) and O's (blue)
- 📊 Score tracking system
- 🔄 Game counter
- 💫 Turn indicator
- 🖥️ Cross-platform compatibility (Windows, macOS, Linux)
- 🎛️ Game control buttons (Reset Game, New Game)

## Requirements

- Python 3.x
- Tkinter (usually comes pre-installed with Python)

## Installation

1. Ensure you have Python 3.x installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

2. Clone the repository or download the source code:
```bash
git clone <repository-url>
```

3. Navigate to the project directory:
```bash
cd tic-tac-toe
```

## Usage

1. Run the game:
```bash
python tic_tac_toe.py
```

2. Game Rules:
   - Players take turns clicking empty squares to place their symbol (X or O)
   - First player to get three of their symbols in a row (horizontally, vertically, or diagonally) wins
   - If all squares are filled and no player has won, the game is a tie
   - Use "Reset Game" to start a new round while keeping scores
   - Use "New Game" to reset everything including scores

## Controls

- Left-click on any empty square to place your symbol
- "Reset Game" button: Clears the board for a new round while maintaining scores
- "New Game" button: Resets everything including scores and game counter

## Game Interface Elements

- Title header
- Score display showing X wins, O wins, ties, and total games played
- Turn indicator showing current player
- 3x3 game grid
- Control buttons for game management

## Technical Details

The game is built using:
- Python 3.x
- Tkinter for GUI
- Object-oriented programming principles
- Platform-specific optimizations for macOS

## Customization

You can customize the game's appearance by modifying these variables in the code:

```python
self.BUTTON_FONT = ("Lato", 24, "bold")
self.LABEL_FONT = ("Lato", 16)
self.BUTTON_BG = "#3E3A44"
self.BUTTON_ACTIVE_BG = "#6C63FF"
self.TEXT_COLOR = "#E1E1E1"
self.X_COLOR = "red"
self.O_COLOR = "blue"
```

## Known Issues and Solutions

### macOS Users
If you encounter button height warnings, the game includes built-in fixes for macOS compatibility. These warnings don't affect gameplay:
```
Warning: Expected min height of view: (<NSButton: ...>) to be less than or equal to 30 but got a height of 32.000000
```

### Common Troubleshooting
1. If the game doesn't start, ensure Python and Tkinter are properly installed
2. For font issues, try changing to a font available on your system
3. For display issues, adjust the window size by modifying button dimensions

## Contributing

Contributions are welcome! Here are some ways you can contribute to this project:
1. Report bugs
2. Suggest enhancements
3. Add new features
4. Improve documentation

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Future Enhancements

Possible future improvements:
- AI opponent
- Customizable player names
- Sound effects
- Animation effects
- Game history logging
- Difficulty levels
- Network multiplayer support

## Acknowledgments

- Thanks to the Python and Tkinter communities
- Inspired by classic Tic Tac Toe implementations
- Dark theme color palette inspired by modern UI design trends
