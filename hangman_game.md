# Task: Hangman Game

**Objective:** Create a simple Hangman game where the player needs to guess a word letter by letter. Write a program in a programming language (e.g., Python) that includes the following topics:

1. Basic concepts: variables, data types, operators.
2. Input and output of data.
3. Loops: while.
4. Conditional statements: if, elif, else.

**Description:**
1. Choose a set of words that will be used in the game. These words will be randomly selected each time the game starts.

2. Upon launching the program, greet the player and explain the rules of the game.

3. Display an empty string with the number of characters corresponding to the length of the chosen word (e.g., "_____" for a five-letter word).

4. Ask the player to enter a letter.

5. Check if the entered letter is in the chosen word:
   - If the letter is present, display a message about a correct guess and show the word with the guessed letters (e.g., "_p__l_").
   - If the letter is not present, display a message about an incorrect guess and reduce the player's "attempts" (e.g., give a total of 6 attempts).

6. Repeat steps 4-5 until the player guesses the word or runs out of attempts.

7. At the end of the game (when the player guesses the word or uses all attempts), display an appropriate message about victory or defeat.

8. After finishing the game, ask the player if they want to play again. If the answer is positive, start a new game from step 2. Otherwise, end the program with a farewell message.

**Example Output:**
```
Welcome to Hangman!

Rules of the game:
1. You need to guess the word letter by letter.
2. You have 6 attempts to guess the letters.

Word: _____

Enter a letter: e
Correct! Word: __e___

Enter a letter: p
Correct! Word: __e__p

Enter a letter: r
Incorrect! You have 5 attempts left. Word: __e__p

...

Enter a letter: l
Correct! Word: __e__pl

Enter a letter: o
Incorrect! You have 1 attempt left. Word: __e__pl

Enter a letter: t
Incorrect! Game over. The word was: "example"

Do you want to play again? (yes/no): yes

Welcome to Hangman!
...
```

**Note:**
Don't forget to add some graphical elements, for example, drawing the hangman and the hanged person depending on the number of remaining attempts. This will make the game more engaging and visually appealing.

---
Please note that the game implementation provided in the example output is a textual representation. You can enhance the game by adding graphics, sound effects, or implementing it as a graphical application if you are comfortable with GUI programming.