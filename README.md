# Chess Master — Python Chess Game

A modern, polished chess game built in Python with a beautiful Tkinter GUI and a smart AI opponent. Chess Master is a great project for learning game programming, GUI development, and classic board-game algorithms such as Minimax with Alpha–Beta pruning.

Play against the computer or a friend on the same machine, track move history, enjoy sound effects, and experience a realistic AI thinking delay.

---

## Features

- Play vs AI (Minimax with Alpha–Beta pruning)
- Play vs Human (same computer / local two-player)
- Configurable timers (example: 10 minutes per side)
- Scrollable move history (game log)
- Sounds for moves, captures, check, and game over
- Pawn promotion (Queen, Rook, Bishop, Knight)
- Flip board option (rotate the board)
- Restart & Quit options
- Clean and responsive Tkinter GUI with chess piece images
- AI “thinking” delay for realism

---

## Screenshots

Start Menu  
![Start Menu](screenshots/start.png)

In-Game (vs AI)  
![Gameplay](screenshots/game.png)

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Aqibahmed12/Chess-Master.git
cd Chess-Master
```

2. (Optional but recommended) Create and activate a virtual environment:
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS / Linux
source venv/bin/activate
```

3. Install required dependencies:
```bash
pip install -r requirements.txt
```

4. Run the game:
```bash
python chess_game.py
```
(If the main script has a different name in the repo, run that file instead — e.g., `python main.py`)

---

## Controls

- Click a piece to select it, then click a destination square to move.
- Use the "Flip Board" button to rotate the board orientation.
- Use "Restart" to start a new game.
- Use "Quit" to return to the main menu or close the game.
- When a pawn reaches the end of the board, choose a promotion piece from the dialog.

---

## Requirements

- Python 3.8+
- Tkinter (usually included with Python)
- python-chess
- pygame
- Pillow (PIL)

Install them with:
```bash
pip install -r requirements.txt
```

---

## Architecture & Notes

- AI is implemented using Minimax with Alpha–Beta pruning for efficient search.
- The GUI is implemented with Tkinter and uses image assets for pieces.
- Sound is handled via pygame (or the configured audio backend).
- The move history supports scrolling and copy/export features (if implemented).

This project is ideal for:
- Learning Minimax and search optimizations
- Practicing Python GUI development (Tkinter)
- Building game features such as timers, move logs, and UIs

---

## Contributing

Contributions are welcome! If you'd like to:
- Report bugs: open an issue
- Request features: open an issue with your idea
- Submit code: open a pull request

Please follow the repository's contribution guidelines (if present).

---

## Author

Aqib Ahmed  
Student — BS Artificial Intelligence, Aror University, Sukkur, Pakistan

---

## Support

If you like this project, please star the repo and share it with others. Your support helps me keep improving this project — thank you!

