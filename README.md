# Blackjack Python Program

A command-line Blackjack program written in Python, utilising random card generation and core game logic to simulate an accurate Blackjack game.

## Features
- Uses core Blackjack rules, including score calculation and win/loss outcomes
- Simulates gameplay between the player and the CPU.
- Interactive menu system, allowing the user to repeat play sessions or stop the program
- Randomised card drawing using Python's random module

## How It Works
The program simulates a Blackjack game between the player and the CPU as the Dealer.
Cards are drawn at random and added to each player's hands. The player can choose to continue drawing cards or stand. The dealer follows predefined logic to determine its actions.

The game ends when:
- Either the player or the Dealer goes over 21 (bust)
- The player chooses to stand and the dealer finishes drawing

After each round has elapsed, the program prompts the user to play again or exit the program.

## How to Run
1. Download the Python file
2. Run in Python via terminal or IDE
3. Follow the menu instructions:
"Do you want to play a game of Blackjack? Type 'y' or 'n': "

## Technologies used
- Python
- random module

## Future Improvements
- Implement full deck logic with face cards (Jack, Queen, King) and proper Ace Handling
- Improve dealer AI behaviour for a more realistic simulation
- Add statistics tracking features (e.g. how often player has won and/or lost, number of Blackjacks, etc.)
- Refactor code for improved scalability and readability
