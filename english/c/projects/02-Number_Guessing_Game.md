
# Number Guessing Game

## Description
The aim of this project is to create a number guessing game in the C language, where the computer randomly selects a number and the user tries to guess it. This game is a simple example of user-program interaction.

## Project Assumptions
- The program randomly generates a number within a specified range (e.g., from 1 to 100).
- The user's task is to guess this number by entering their guesses.
- After each guess, the program informs the user if their number is too high, too low, or correct.
- The game ends when the user guesses the number or after a specified number of attempts.

## Functionality
1. **Random Number Generation**: The program should initially randomly select a number.
2. **Guessing Process**: The user should be able to enter their guess number.
3. **Evaluation of Guess**: The program should evaluate the guessed number and give appropriate hints to the user.
4. **End Game Conditions**: The game ends successfully (number guessed) or after exceeding the number of attempts.

## Implementation Tips
- Use functions for generating random numbers, like `rand()`.
- Implement a loop that allows for multiple guesses of the number until it is guessed or the limit of attempts is reached.
- Remember to provide suitable messages to the user.

## Educational Goal
This project allows for practical application of elements of the C language, such as random number generation, loops, conditional statements, and basic input/output.
