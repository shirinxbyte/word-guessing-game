
# Word Guessing Game

This is a simple word guessing game built with Python.  
The player has to guess a randomly chosen word one letter at a time.  
If the player guesses all letters within the allowed number of attempts, they win! Otherwise, they lose.

## How to Play

- Run the Python script `word_guessing_game.py`.
- You will see underscores `_` representing each letter in the hidden word.
- Enter one letter per guess.
- If the letter is in the word, it will be revealed in the correct position(s).
- You have 10 attempts to guess the entire word.

## Features

- Random word selection from a word bank.
- Shows current guessing progress after each guess.
- Keeps track of remaining attempts.
- Displays a congratulation message when the player wins.
- Shows the correct word when the player runs out of attempts.

## Requirements

- Python 3.x

## How to Run

1. Clone the repository or download the `word_guessing_game.py` file.
2. Open a terminal or command prompt in the project folder.
3. Run the game with the command:

```bash
python3 word_guessing_game.py
````

## Example

```
Current word: _ _ _ _ _
Guess a letter: t
Great guess!

Current word: t _ _ t _
Guess a letter: o
Great guess!

...

Congratulations!! You guessed the word: tiktok
```

## License

This project is open-source and free to use.

---

Enjoy the game! 🎉

