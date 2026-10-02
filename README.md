# Deal or No Deal

A desktop Java game inspired by the popular TV show where the player chooses a box, opens others, and decides whether to accept the banker’s offer or continue playing for a bigger prize.

## Overview

This project is a Java Swing application that recreates the classic Deal or No Deal gameplay loop. Each round includes:

- 26 boxes with randomly assigned prize amounts
- A selected player box that remains hidden until the end
- Sequential rounds where boxes are opened
- Banker offers that evolve based on remaining values and the current game state
- A final decision to accept or reject the offer

## Features

- Interactive Swing-based user interface
- Randomized prize distribution
- Dynamic banker offer calculation
- Game progression through multiple rounds
- Visual money board for remaining values
- Win/lose final outcome based on the player’s chosen box

## Gameplay

1. The game starts by assigning random prize values to 26 boxes.
2. The player selects one box as their initial choice.
3. The player opens boxes in rounds while the remaining values are shown on the board.
4. After a set number of boxes are opened, the banker makes an offer.
5. The player chooses to accept the deal or continue playing.
6. The game ends when the player accepts a deal or reaches the final reveal.

## Project Structure

```text
.
├── Main.java
├── Banker.class
├── Box.class
├── BoxButtonAction.class
├── ButtonAction.class
├── Game.class
├── GameScreen.class
├── GameValue.class
├── Money.class
├── Main.class
├── actButtonsActions.class
└── README.md
```

## Technologies Used

- Java
- Swing (GUI framework)
- AWT event handling

## Requirements

- Java JDK 8 or later
- A desktop environment capable of running Swing applications

## Run the Game

From the project directory, compile and run:

```bash
javac Main.java
java Main
```

If you are using a Java environment with automatic classpath handling, the game can also be launched directly with your IDE by running `Main`.

## Notes

This project is designed as a fun Java desktop game and demonstrates GUI development, event-driven programming, and game logic implementation in Java.

## License

This project is provided as-is for educational and personal use.
