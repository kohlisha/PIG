Welcome to the PIG Game!

This is a Python-based game that simulates a dice-rolling challenge for 2-4 players. Players take turns rolling a six-sided die, aiming to reach a target score of 50 before their opponents. However, if a player rolls a 1, their turn ends immediately, and they lose any points accumulated during that turn.

Gameplay Instructions:

Run the code: Ensure you have Python installed on your system. Open a terminal or command prompt, navigate to the directory where you've saved the code, and execute it using the com0mand python pig.py.

Enter the number of players: When prompted, type in the number of players participating (2, 3, or 4).

Take turns rolling: Each player's turn will begin with the option to roll the die. Enter "y" to roll, or any other key to end your turn.

Accumulate points: If you roll a number other than 1, its value will be added to your current score. You can continue rolling until you either choose to stop or roll a 1, ending your turn.

Reach the target score: The first player to reach or exceed the target score of 50 wins the game!

Code Structure:

import random: Imports the random module for generating random numbers.
def roll():: Defines a function to simulate a dice roll, returning a random integer between 1 and 6.
while True:: Main game loop that continues until a player reaches the target score.
Input validation: Ensures the number of players entered is valid (2-4).
Player turns: Iterates through each player's turn, handling input, rolling the die, and updating scores.
Winning condition: Checks if any player has reached the target score and declares the winner.
