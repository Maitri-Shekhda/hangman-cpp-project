# Hangaman

Welcome to the Hangman game repository! This simple C++ program allows you to play the classic word-guessing game where you try to guess a word letter by letter before you run out of attempts.

## Overview
This Hangman game has several key components and functionalities:

Word Selection: The program reads a list of words from a file and randomly selects one for the player to guess.

Game Logic: The main function initializes the game by selecting a random word and setting up the initial conditions. It allows the player to guess either the entire word or individual letters. The game tracks the number of remaining tries and updates the displayed word with correct guesses.

Win/Lose Conditions: If the player guesses the word correctly within the allowed tries, they win. If the player runs out of tries without guessing the word, they lose.

User Interaction: The game provides prompts for the player to input their guesses and displays feedback on whether their guesses are correct.

## How to play
Clone this repository to your local machine.

bash
Copy code
git clone <repository_url>
Navigate to the directory containing the cloned repository.

bash
Copy code
cd Hangman_Game
Compile the C++ program.

Copy code
g++ hangman.cpp -o hangman
Run the compiled executable.

bash
Copy code
./hangman
Follow the prompts to guess the word or letters. You have a limited number of attempts to guess the word correctly.

If you guess the word correctly within the allowed tries, you win. Otherwise, you lose.

## Customization
You can customize the game by modifying the word list file (words.txt). Simply add or remove words from the file to change the pool of words from which the game selects.

## Contributing
Maitri

If you have any suggestions for improvements or find any bugs, feel free to open an issue or submit a pull request.
