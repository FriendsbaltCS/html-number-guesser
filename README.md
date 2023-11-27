# Number Guesser Game

In this project, you will create a simple higher-or-lower number guessing game. The computer will think of a secret number from 1 to 1 Million, and ask you to guess it. After each guess, the computer will tell you whether the number is higher or lower. You win if you can guess the number within 20 tries.

## Specifications

The interface for this project will be a simple HTML page. The skeleton of the page is already provided in `index.html`. You will need to write the JavaScript to make the game work, though you may modify the HTML and CSS if you wish or as necessary.

The game should work as follows:
1. The computer will think of a secret number between 1 and 1 Million.
2. The user will enter a guess into the text field and press the "Guess" button.
3. This will trigger the JS event listener for the "Guess" button, which will:
    1. Check if the guess is correct. If so, the user wins and the game is over.
    2. If the guess is incorrect, the computer will tell the user whether the guess was too high or too low and display the number of guesses remaining.
    3. The user will have 20 tries to guess the number correctly. If they run out of tries, they lose and the game is over.

### Outputs
Each guess will be displayed below the text field. If the guess is too low, the guess will be displayed with the text "Too low". If the guess is too high, the guess will be displayed with the text "Too high". If the guess is correct, the guess will be displayed with the text "Correct!". If the user runs out of guesses, the guess will be displayed with the text "You lose!".

As an added bonus, you can also change the display color of the guess to red if it is too low, blue if it is too high, and green if it is correct (or any other colors you wish).

When the game ends, the "Guess" button should be disabled.

### Inputs
The user will enter their guess into the text field and press the "Guess" button. You can assume that the user will enter a valid integer between 1 and 1 Million. However, if you wish, you can add additional validation to the input and alert the user if they enter an invalid guess.

### AI Policy
You should not use Copilot for this project.