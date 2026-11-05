
# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a word-guessing game in Python. Practice using strings, loops, conditionals, user input, and random selection as you reveal a hidden word before running out of attempts.

## 📝 Tasks

### 🛠️ Set Up the Game

#### Description
Choose a secret word from the provided word list and initialize the variables needed to track the player's guesses and remaining attempts.

#### Requirements
Completed program should:

- Randomly select one word from the predefined `words` list.
- Keep track of the letters the player has guessed.
- Track the number of incorrect guesses and the maximum number allowed.

### 🛠️ Run the Guessing Loop

#### Description
Repeatedly show the player's progress and prompt for a letter until the player guesses the word or runs out of attempts.

#### Requirements
Completed program should:

- Display each letter that has been guessed correctly and an underscore for each letter that has not.
- Ask the player to enter a letter on each turn.
- Update the game state after each guess, reducing the remaining attempts for an incorrect guess.

### 🛠️ Finish the Game

#### Description
End the game when the player has guessed the secret word or used all allowed incorrect guesses, and report the outcome.

#### Requirements
Completed program should:

- Stop accepting guesses when either end condition is met.
- Display a win message when the player guesses the word.
- Display a lose message when the player runs out of attempts.
