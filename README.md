# Hangman

Welcome to the Hangman game repository! This simple C++ program allows you to play the classic word-guessing game where you try to guess a word letter by letter before you run out of attempts.

## Overview
This Hangman game has several key components and functionalities:

Word Selection: The program reads a list of words from a file and randomly selects one for the player to guess.

Game Logic: The main function initializes the game by selecting a random word and setting up the initial conditions. It allows the player to guess either the entire word or individual letters. The game tracks the number of remaining tries and updates the displayed word with correct guesses.

Win/Lose Conditions: If the player guesses the word correctly within the allowed tries, they win. If the player runs out of tries without guessing the word, they lose.

User Interaction: The game provides prompts for the player to input their guesses and displays feedback on whether their guesses are correct.

## How to play
**Clone this repository to your local machine.** 

git clone https://github.com/Maitri-Shekhda/hangman-cpp-project.git

**Navigate to the directory containing the cloned repository.**

cd hangman-cpp-project

**Compile the C++ program.**

g++ hangman.cpp -o hangman

**Run the compiled executable.**

./hangman

Follow the prompts to guess the word or letters. You have a limited number of attempts to guess the word correctly.

If you guess the word correctly within the allowed tries, you win. Otherwise, you lose.

## Customization
You can customize the game by modifying the word list file (words.txt). Simply add or remove words from the file to change the pool of words from which the game selects.

## Contributing
Maitri
Contributions are welcome! If you have any suggestions or improvements, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change

## Liscence
This project is open-source and available under the MIT License.
