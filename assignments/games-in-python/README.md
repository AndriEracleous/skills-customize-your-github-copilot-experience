
# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a playable Hangman game in Python that uses loops, conditionals, and string handling to manage guesses and game state.

## 📝 Tasks

### 🛠️	Set Up the Game

#### Description
Create the basic game setup, including the word list and the initial display of the hidden word.

#### Requirements
Completed program should:

- Store a list of possible words in code
- Randomly select one word to guess
- Display the word as underscores with spaces (example: `_ _ _ _`)


### 🛠️	Handle Guesses and End the Game

#### Description
Prompt the player for letter guesses, update the display, track remaining attempts, and finish the game with a win or loss message.

#### Requirements
Completed program should:

- Accept a single-letter guess from the user each turn
- Reveal correctly guessed letters in the word display
- Decrease remaining attempts for incorrect guesses
- End when the word is fully guessed or attempts reach zero
- Print a clear win or lose message
