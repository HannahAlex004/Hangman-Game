# Hangman-Game
SEM III _C++_MiniProject

## Description
The Hangman Game Project is a C++ console-based application that simulates the classic 
word-guessing game. The program allows players to guess the name of a randomly selected 
game, with a limited number of attempts. The game data, including names and descriptions, 
is read from an external file ("games.txt").
The Hangman Game Project is implemented in C++ and uses a simple console interface. The 
game reads a list of video games and their descriptions from an external file (games.txt). 
Players attempt to guess the name of a randomly selected game by inputting one letter at a 
time. The game provides feedback on correct and incorrect guesses, displaying a hangman 
figure to visualize the player's progress.
## Files
hangman.cpp: The main C++ source code file containing the implementation of the 
Hangman game. 
games.txt: A text file containing a list of video games and their descriptions in the format 
<game_name>:<game_description>. 
## Key Components
Key Components : 
#### 1. Game Struct: Holds information about a game, including its name and description. 
#### 2. File Input: Utilizes file input/output to read game data from "games.txt." 
#### 3. Random Game Selection: Randomly selects a game from the provided list for each round. 
#### 4. Hangman Display: Displays a hangman figure to visually represent the player's progress and incorrect guesses. 
#### 5. Word Display: Displays the current state of the word, revealing guessed letters and hiding others. 
#### 6. Gameplay Loop: Implements a loop allowing players to make guesses until they either correctly identify the game or run out of attempts. 
#### 7. Scoring System: Awards scores based on the number of correct guesses and remaining attempts. 
#### 8. Player Interaction: Prompts players to input guesses, handles input validation, and checks for duplicate guesses. 
#### 9. Game Outcome: Informs players of the game outcome (win/lose) and displays the correct game name if the player loses. 
#### 10. Restart Option: Allows players to choose whether to play again or exit the program. 
## How to Play 
#### 1. Compile the Code: Ensure you have a C++ compiler installed. Compile the code using a command like g++ hangman.cpp -o hangman. 
#### 2. Run the Game: Execute the compiled program, e.g., ./hangman. 
#### 3. Gameplay: Follow the on-screen instructions to guess the name of the randomly selected video game. Input one letter at a time. The game provides feedback on correct and incorrect guesses and displays a hangman figure. 
#### 4. Outcome: The game concludes either when the player correctly guesses the game or runs out of attempts. The correct game name and description are revealed regardless of the outcome. 
#### Enjoy playing Hangman!
