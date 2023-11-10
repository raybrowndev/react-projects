# Rock, Paper, Scissors Game

## Overview
Welcome to the Rock, Paper, Scissors game! This react web application allows users to play the classic game against the computer. Simply enter your nickname, make a choice between Rock, Paper, or Scissors, and see who wins!

## Game Preview

https://github.com/raybrowndev/react-projects/assets/78723108/1fb496a0-9616-4801-aa48-139786658f74


### Features
- **Components:** The application is structured using React components for better organisation and reusability. 
    Key components include:
  - **PlayerName:** Displays the player's nickname.
  - **Rock, Paper, Scissors:** Icons for player choices.

- **State Management:** The game state is managed using React Hooks (useState). 
    Key states include:
  - `playerChoice:` Tracks the player's current choice.
  - `computerChoice:` Tracks the computer's random choice.
  - `playerScore` and `computerScore:` Keep track of the scores for both the player and the computer.
  - `playerName:` Stores the player's nickname.
  - `submitted:` Manages the submission status of the player's nickname.
- **Conditionals:** Conditional rendering is used to display different content based on the game state. For instance:
  - The game result is displayed only when the player makes a choice.
  - The PlayerName component is conditionally rendered based on the submission status.
- **Objects and Array Methods:** Arrays and objects are utilised to manage choices and messages in the game.
  - The `choices` array stores the possible game choices.
  - The `messages` object holds win, lose, and draw messages.
- **Multiclass Design:** The application follows a clean and modular design with separate classes for styling and layout.
- **Input Fields:** Users can enter their nickname in an input field before playing the game.
- **Scoreboard:** Displays the current scores for the player and computer.
- **Restart Functionality:** Players can restart the game by clicking the "RESTART" button.


## How to Play
1. Enter your nickname in the provided input field.
2. Choose Rock, Paper, or Scissors by clicking the corresponding icon.
3. See the result of the game displayed below the choices.
4. Check the scoreboard to see the current scores.
5. Restart the game at any time by clicking the "RESTART" button.

<p align="center">
  <em>Thank you for checking out my project! 🚀</em>
</p>
