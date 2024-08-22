# Higher or Lower Game

This is a simple "Higher or Lower" game implemented in Python. The game challenges players to guess which of two famous personalities or organizations has more followers on social media.

## Features

- Compare follower counts between two famous personalities or organizations.
- Simple command-line interface for user interaction.
- Dynamic score tracking.

## How to Play

1. The game will present two accounts (e.g., celebrities, companies) and their descriptions.
2. You need to guess which one has more followers by typing 'A' or 'B'.
3. If you guess correctly, your score increases, and you continue to the next round with a new comparison.
4. If you guess wrong, the game ends, and your final score is displayed.

## Setup and Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/your-repository-name.git

2. Navigate to the project directory:
   cd your-repository-name

3. Run the game:
   python Higher_or_Lower.py

## Project Structure

art.py: Contains ASCII art for the game logo and other visual elements.
game_data.py: Contains a list of dictionaries with data about various famous personalities and organizations, including their follower counts.
Higher_or_Lower.py: The main script that runs the game, including logic for comparing follower counts, user interaction, and score tracking.
