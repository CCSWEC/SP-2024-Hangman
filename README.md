# SP-2024-Hangman
Hangman game for spring 2024 project
You will be making a hangman project, here is the basic idea.

https://prod.liveshare.vsengsaas.visualstudio.com/join?825189D51D96F2E03B42C2B012FAEC80EA60

Define a list of words: Create a list of words that the player will have to guess. This list can be stored as an array or a list in your code.

Select a random word from the list: Use a random number generator to select a word from the list of words. This will be the word that the player needs to guess.

Display the hangman: Create a simple ASCII art representation of the hangman that updates as the player makes incorrect guesses.

Display the word to be guessed: Display dashes or underscores to represent the letters of the word that need to be guessed. For example, if the word is "hangman", display "------" to start.

Prompt the player to guess a letter: Ask the player to input a letter to guess. Make sure to handle input validation to ensure that the player only enters valid alphabetic characters.

Check if the guessed letter is in the word: Compare the guessed letter with the letters in the word. If the guessed letter is in the word, update the displayed word to reveal the correct letters. If the guessed letter is not in the word, update the hangman display.

Keep track of incorrect guesses: Keep track of the number of incorrect guesses made by the player. Once the player reaches a certain number of incorrect guesses (e.g., 6 for the traditional hangman game), end the game.

Check for win/lose conditions: Check if the player has guessed all the letters in the word correctly or if they have reached the maximum number of incorrect guesses. Display a message to inform the player of the outcome.

Allow the player to play again: Give the player the option to play again once the game has ended. Reset the game state and select a new word for the player to guess.

Challenges (These do not have to be implented, feel free to attempt them if you can :) )
  1. Store all properly guessed words in a text file that can be viewed
  2. Use a file to store all words and have computer read all the words into an array then pick a random one as the guess word (basically try not to hardcode the words in the program).
  3. add a time limit
  4. Implement a highscore feature

reach out to togunleye1@collin.edu if you have any questions
