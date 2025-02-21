Dice Game - React

A simple dice game built with React.js and styled-components, where users can select a number, roll a dice, and calculate their score based on the dice result. The game includes various features such as number selection, dice rolling, score reset, and game rules display.

Features

Number Selector: Choose a number between 1 and 6.
Roll Dice: Click on the dice image to roll the dice.
Score Calculation: If the selected number matches the rolled dice number, you score the same number of points. If not, 2 points will be deducted.
Validation: If you click on the dice without selecting a number, you will see a validation error message.
Reset Score: A button to reset your score.
Show Rules: Toggle button to show or hide game rules.

How to Play

1. Select a Number: Choose a number between 1 and 6.
2. Click on the Dice: After selecting a number, click on the dice to roll.

3. Scoring:

If the selected number matches the dice roll, you earn the same points as the rolled number.
If the guess is wrong, 2 points will be deducted from your score.
4. Reset Score: Press the "Reset Score" button to start over with a fresh score.
5. View Rules: Press the "Show Rules" button to toggle the game rules.

Tech Stack

React.js: A JavaScript library for building user interfaces.
Vite: A fast development build tool for React.
Styled-Components: A CSS-in-JS solution for styling React components.

Components

GamePlay: Manages the overall gameplay and score display.
NumberSelector: Allows users to select a number between 1 and 6.
RollDice: Handles the dice rolling logic and display.
StartGame: Displays the game start button and initializes the score.
TotalScore: Displays the total score of the user.
Rules: A toggleable component that shows or hides the game rules.


Installation:

To get started with this project, follow these steps:

1. Clone the repository:

git clone https://github.com/wasif-cyber/React-Project-3.git
cd dice-game

2. Install dependencies:

npm install

3. Start the development server:

npm run dev