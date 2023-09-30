# Hangman Game

Welcome to the Hangman Game! This simple Java console game allows you to guess a word letter by letter within a limited number of attempts. The game randomly selects a word from a predefined list of words, and your task is to guess the word correctly.

## How to Play

1. **Setup**: Compile and run the `HangmanGame.java` file using a Java development environment or IDE.

2. **Game Start**: Once the game starts, you will receive a warm welcome message, and the maximum number of attempts allowed will be displayed.

3. **Guessing the Word**: You will see underscores representing the letters of the word to guess. Your task is to guess the word by entering one letter at a time.

4. **Input**: Enter a letter and press Enter. The game will check if the letter is in the word:
   - If the letter is in the word, it will be revealed in its correct position, and you will receive a "Good guess!" message.
   - If the letter is not in the word, you will be informed with a "Sorry, that letter is not in the word." message, and the number of attempts will be reduced.

5. **Winning**: Continue guessing letters until you have guessed the entire word correctly, or you run out of attempts. If you correctly guess all the letters in the word, you win the game.

6. **Game Result**: After the game ends, you will receive one of the following messages:
   - If you correctly guess the word: "Congratulations! You guessed the word: [word]"
   - If you run out of attempts: "You ran out of attempts. The word was: [word]"

7. **Restart**: To play again, simply run the `HangmanGame.java` file again.

## Word Categories

The game includes words from various categories, such as:
- Fruits
- Animals
- Vehicles
- Electronics
- Programming
- Nature
- Music
- Literature
- Food

The words are randomly selected from these categories, providing variety in each game.

Have fun playing Hangman and challenging your word-guessing skills!
