# Project Statement

## Project Title
**High or Low Number Guessing Game**

## Project Author
**Aman Patel**

## Project Guide
**Dr. Dheeresh Soni**

## 1. Problem Statement
The High or Low Number Guessing Game is a command-line Python application in which a player predicts whether the next randomly generated number will be higher or lower than the current number. The project provides a simple interactive environment for practicing logical decision-making and understanding basic programming concepts such as conditional statements, loops, functions, random number generation, user input, and lists.

The game maintains a score as the player makes predictions. A correct prediction increases the score, an incorrect prediction decreases it, and equal consecutive numbers do not change the score. A game ends after the maximum number of rounds or when the score reaches zero.

## 2. Scope of the Project
The project is a single-player, text-based game that runs in a Python environment. It generates numbers from 1 to 200 and allows a player to complete up to 10 rounds in one game, subject to the score-ending condition.

The project includes:
- A menu to start a game, view the rules, view the leaderboard, or exit.
- Player-name input and validation to prevent an empty name.
- Random number generation and HIGH/LOW predictions.
- Score updates based on the result of each prediction.
- A final score and performance message at the end of a game.
- A leaderboard that records completed games during the current program session.

The current implementation does not include a graphical interface, online multiplayer, persistent leaderboard storage, or a database.

## 3. Target Users
- Students learning Python programming.
- Beginners interested in simple command-line games.
- Users who want a short number-prediction game.

## 4. High-Level Features
1. **Main menu:** Provides options to play, read the rules, view the leaderboard, and exit.
2. **Player input:** Requests a player name and repeats the prompt if the name is empty.
3. **Rules display:** Explains the number range, scoring, round limit, and score-ending condition.
4. **HIGH/LOW prediction:** Accepts HIGH/LOW (or H/L) as the player's choice.
5. **Random number generation:** Generates the starting number and each subsequent number in the range 1–200.
6. **Score management:** Awards 10 points for a correct prediction, deducts 5 points for an incorrect prediction, and makes no change for equal numbers.
7. **Game completion:** Ends after 10 rounds or when the score is no longer above zero, then displays the final score and a performance message.
8. **Leaderboard:** Stores and displays scores and player names for games played during the current run of the program.

