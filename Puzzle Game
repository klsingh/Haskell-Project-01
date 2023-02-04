import Control.Monad

-- A puzzle game where the user must guess a number
puzzleGame :: IO ()
puzzleGame = do
  putStrLn "Welcome to the puzzle game!"
  putStrLn "I'm thinking of a number between 1 and 10. Can you guess it?"
  secret <- randomRIO (1,10)
  let gameLoop = do
        putStr "Enter your guess: "
        guess <- readLn
        if guess == secret
          then putStrLn "You guessed it! You win!"
          else do
            putStrLn "Sorry, that's not it. Try again."
            gameLoop
  gameLoop

main :: IO ()
main = puzzleGame
