# Mastermind Game

Welcome to the Mastermind game! This is a command-line version of the classic code-breaking game where you have to guess a secret code within a limited number of tries.

## How to Play

The computer generates a random secret code consisting of 4 colors. Your task is to guess the code. After each guess, you'll receive feedback on how many colors are in the correct position and how many colors are correct but in the wrong position.

### Colors

The valid colors are:
- R (Red)
- G (Green)
- B (Blue)
- Y (Yellow)
- W (White)
- O (Orange)

### Rules

1. You have 10 attempts to guess the correct code.
2. Each guess must be exactly 4 colors.
3. After each guess, you will receive feedback in the form of:
   - Correct Positions: Number of colors that are correct and in the correct position.
   - Incorrect Positions: Number of colors that are correct but in the wrong position.

### Example

If the secret code is `R G B Y` and your guess is `R B G Y`, the feedback will be:
- Correct Positions: 2 (R and Y)
- Incorrect Positions: 2 (B and G are correct colors but in the wrong positions)

## Getting Started

### Prerequisites

- Python 3.x

### Running the Game

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/mastermind-game.git

2. Navigate to the project directory   
 ```sh
   cd mastermind-game
 
3 . run the game  
```sh
   python mastermind.py   

