# HANGMAN-GAME
This project is implemented in C

Hangman is a guessing game for two or more players. One player thinks of a word, phrase or sentence and the other(s) tries to guess it by suggesting letters within a certain number of guesses. Originally a Paper-and-pencil game, there are now electronic versions. The word to guess is represented by a row of dashes representing each letter of the word. Rules may permit or forbid proper nouns, such as names, places, brands, or slang. If the guessing player suggests a letter which occurs in the word, the other player writes it in all its correct positions. If the suggested letter does not occur in the word, the other player removes (or alternatively, adds) one element of a hanged stick figure as a tally mark. Generally, the game ends once the word is guessed, or if the stick figure is complete — signifying that all guesses have been used. The player guessing the word may, at any time, attempt to guess the whole word. If the word is correct, the game is over and the guesser wins. Otherwise, the other player may choose to penalize the guesser by adding an element to the diagram. On the other hand, if the guesser makes enough incorrect guesses to allow the other player to complete the diagram, the guesser loses. However, the guesser can also win by guessing all the letters that appear in the word, thereby completing the word, before the diagram is completed.

ALGORITHM

Step 1: Start

Step2: Display the rules of the game.

Step 3: Create an array of encrypted words, and select one randomly as the target word.

Step 4: Create an array of spaces to represent the target word, with each space representing letter.

Step 5: Create an array to keep track of incorrect guesses.

Step 6: Start a loop to take input of the player's guess and update the target word array and incorrect guess array.

Step 7: Display the number of mistakes and a hangman figure based on the number of incorrect guesses.

Step 8: End the loop when the target word is completely filled or the number of incorrect guesses reaches 6.

Step 9: Display the result (win or lose) and the target word.

Step 10: End
