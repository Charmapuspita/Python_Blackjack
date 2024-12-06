Capstone Project: Blackjack

🃏 Blackjack Game in Python
This project implements a simplified version of the popular card game Blackjack. The game allows a single user to play against a computer dealer using Python. The program simulates card drawing, score calculation, and game rules, providing an interactive command-line experience.
________________________________________
📋 Features
•	A deck of cards is simulated with numbers from 1 (Ace) to 10, with face cards also represented as 10.
•	Implements Blackjack scoring rules:
o	Aces can count as 1 or 11.
o	A score of exactly 21 with the first two cards is a Blackjack.
•	Provides automated dealer behavior:
o	Dealer draws cards until their score is at least 17.
•	Handles game-winning conditions:
o	Win, lose, or draw, based on the player's and dealer's scores.
o	Automatic wins for Blackjack.
•	Interactive gameplay:
o	Player decides whether to draw another card or pass.
o	The game runs in a loop until the player chooses to stop.
________________________________________
🚀 How to Run
1.	Clone the Repository
2.	Ensure Python is Installed: This project requires Python 3.x. You can download it here.
3.	Run the Script:
bash
Copy code
python Capstone_Blackjack.py
4.	Play the Game:
o	Follow the on-screen instructions to play.
o	Decide whether to draw another card or pass.
o	Try to beat the computer dealer by scoring closer to 21 without going over!

________________________________________
🛠️ Code Overview
Key Functions
1.	deal_card():
o	Returns a random card from the deck.
o	Simulates the process of drawing a card.
2.	calculate_score(cards):
o	Calculates the score for a given hand of cards.
o	Handles special conditions like Blackjack and Ace adjustment.
3.	compare(u_score, c_score):
o	Compares the scores of the user and dealer.
o	Determines the outcome: win, lose, or draw.
4.	play_game():
o	Manages the entire game flow, including user interactions and dealer actions.
________________________________________
Flow of the Game
•	The user starts with two cards, as does the dealer.
•	The user can draw additional cards until they pass or exceed 21.
•	The dealer continues drawing cards until their score is at least 17.
•	The game determines the winner based on Blackjack rules.

