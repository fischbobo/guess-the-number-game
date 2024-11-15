# guess-the-number-game
Overview
Game Objective: The player needs to guess a four-digit number composed of different digits.
Hint Mechanism:
A: Indicates that the digit and its position are correct.
B: Indicates that the digit is correct but the position is incorrect.
For example, if the player guesses "9510" and the answer is "9081", they will receive the hint "1A2B": 1A indicates that one digit (9) is in the correct position and value; 2B indicates that two digits (0 and 1) exist in the answer but are in the wrong positions.
Key Features
Input Validation: Ensures that the player inputs a four-digit number with no repeated digits.
History Record: Displays each guess along with its corresponding hint.
Restart Option: Players can click the "Restart" button to reset the game and generate a new random number.
Technology Stack
HTML: Constructs the page structure.
CSS: Beautifies the page style to make it more appealing.
JavaScript: Handles game logic, including generating random numbers, validating input, calculating hints, and managing game state.
Usage Instructions
Open the page, and the system will automatically generate a four-digit answer.
Enter your four-digit guess in the input box.
Click the "Submit" button to view the hint.
Continue guessing based on the hint until you get it right.
Once you guess correctly, click the "Restart" button to reset the game.
