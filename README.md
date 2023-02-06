# Haskell-Project- Puzzle Game

This code defines a puzzle game that generates a random number between 1 and 10, and asks the user to guess the number. The gameLoop function uses the do notation to prompt the user for a guess and read their input, and then checks if the guess is correct. If the guess is correct, the game ends and the user wins. If the guess is incorrect, the game loop continues and the user is prompted to try again.

The puzzleGame function uses the randomRIO function from the Control.Monad library to generate a random number, and then uses the let binding to define the game loop. The main function then runs the puzzle game by calling puzzleGame.
