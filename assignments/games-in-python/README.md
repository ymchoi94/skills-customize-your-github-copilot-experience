
# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a Hangman game in which a player guesses a randomly selected word one letter at a time. Practice using strings, loops, conditionals, user input, and the `random` module.

## 📝 Tasks

### 🛠️ Initialize the Game and Show Progress

#### Description
Complete the game setup by selecting a secret word, initializing the game state, and displaying the letters the player has guessed so far.

#### Requirements
Completed program should:

- Randomly select one word from the provided `words` list.
- Initialize a collection of guessed letters and counters for incorrect guesses and the maximum allowed incorrect guesses.
- Display one underscore for each unguessed letter and reveal letters that have been guessed correctly. For example, a partially guessed word could look like `_ y _ h _ n`.

### 🛠️ Process Guesses and End the Game

#### Description
Use a loop to let the player guess letters, update the game state, and finish when the player guesses the word or runs out of allowed incorrect guesses.

#### Requirements
Completed program should:

- Prompt the player for a letter on each turn and update the displayed word after each guess.
- Track incorrect guesses and stop accepting guesses when the maximum is reached.
- End the game when every letter in the secret word has been guessed or the maximum number of incorrect guesses is reached.
- Display a win message when the word is guessed, or a lose message and the secret word when the player runs out of guesses.
