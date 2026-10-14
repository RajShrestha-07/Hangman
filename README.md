# Hangman

Hangman is a small web game. Guess a hidden computer term one letter at a time. Every wrong guess adds a part to the drawing, and six wrong guesses end the game. Each word comes with a hint, and the word list is made of computer terms like PROCESSOR, ALGORITHM and TRANSISTOR. You can use the on-screen keyboard or your own, and it tracks your wins and losses.

Live demo: 

Built with: HTML, CSS and JavaScript.

What this project shows: The game keeps track of which letters you have guessed in an object, and checks each new letter against the word using `indexOf`. The word on screen is rebuilt after every guess, showing a letter only if it has been guessed. The hangman drawing is an SVG, and each wrong guess makes the next body part visible. The game avoids picking the same word twice in a row, and it listens to real keyboard presses as well as button clicks.

What I'm learning from it: I'm studying how the `guess` function checks a letter and updates the state, how `draw` shows the hidden word, and how the wrong-guess count controls which SVG parts appear.
