# Rock Paper Scissors Game with GUI

A fun and interactive Rock Paper Scissors game built using Python and Tkinter. This project includes a GUI to make the game more user-friendly and visually appealing, with support for multiple rounds, score tracking, and game over messages.

## Features

- Friendly GUI: Clear and intuitive user interface built using Tkinter.
- Multiple Rounds: Play multiple rounds of Rock Paper Scissors.
- Score Tracking: See your score vs. the computer’s score.
- Game Result: After each round, the result is displayed with the choices made by the user and the computer.
- End Game: After a set number of rounds, the game ends with a winner.

## Installation

### Prerequisites

- Python 3.x
- Tkinter (usually comes pre-installed with Python)

### Setup

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/rock-paper-scissors.git
   cd rock-paper-scissors
   ```

2. Install dependencies (if any):
   This project doesn’t require any external dependencies, but ensure you have Python 3.x installed.

3. Run the Game:
   You can run the game using the following command:
   ```bash
   python src/gui.py
   ```

   This will open a window with the game interface. Choose between Rock, Paper, or Scissors to start playing.

## Project Structure

```plaintext
rock-paper-scissors/
├── src/
│   ├── config.py            # Configuration settings (e.g., MAX_ROUNDS)
│   ├── game_logic.py        # Contains game logic: get_computer_choice(), determine_winner()
│   ├── gui.py               # The main GUI file with Tkinter interface
├── README.md                # Project overview and instructions
└── requirements.txt         # If needed in the future for any dependencies
```

## How to Play

- You will see three buttons: Rock, Paper, and Scissors. Click on any of these to make your move.
- The game will randomly generate a move for the computer.
- The result (You won, Computer won, or Draw) will be shown on the screen.
- The score will be updated after each round.
- The game ends after a predefined number of rounds, and the winner will be displayed.

