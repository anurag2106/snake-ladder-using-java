

# Snake and Ladder Game in Java

This is a simple implementation of the classic **Snake and Ladder** game using Java. Two players roll a dice and move across the board, encountering snakes and ladders along the way, aiming to reach the 100th square.

## Table of Contents
- [Description](#description)
- [Gameplay](#gameplay)
- [How to Run](#how-to-run)
- [Game Rules](#game-rules)
- [License](#license)

## Description

The Snake and Ladder game simulates two players taking turns to roll a dice. The game board contains specific positions that either help the player progress (ladders) or send them back (snakes). The first player to reach square 100 wins the game.

### Key Features:
- Two players take turns rolling a dice.
- The game features multiple snakes and ladders which alter the player's position.
- The game automatically checks if a player encounters a snake or a ladder.
- The game continues until one player reaches 100.

## Gameplay

1. Two players roll the dice on each turn.
2. If the player's position after rolling the dice is less than or equal to 100, they can move.
3. If a player lands on a snake or ladder, their position is updated accordingly.
4. The game continues until one player reaches exactly 100, at which point they win.

## How to Run

To run the game, ensure you have Java installed. Follow these steps:

1. Clone or download the repository.
   ```bash
   git clone https://github.com/yourusername/snake-ladder-java.git
   ```

2. Navigate to the project folder and compile the Java file.
   ```bash
   cd snake-ladder-java
   javac SnakeLadder.java
   ```

3. Run the program.
   ```bash
   java SnakeLadder
   ```

4. The game will run in the terminal, showing the progress of both players and the final winner.

## Game Rules

- The board consists of 100 squares.
- Players start at square 0.
- Players take turns to roll a dice (with values between 1 and 6).
- If a player lands on a ladder, they move forward to a higher number.
- If a player lands on a snake, they move backward to a lower number.
- The first player to reach square 100 wins.

### Snakes and Ladders on the Board:
- **Ladders:**
  - Square 2 -> 38
  - Square 9 -> 14
  - Square 15 -> 82
  - Square 16 -> 54
  - Square 50 -> 91
  - Square 74 -> 87

- **Snakes:**
  - Square 18 -> 6
  - Square 24 -> 7
  - Square 61 -> 16
  - Square 72 -> 47
  - Square 96 -> 76


