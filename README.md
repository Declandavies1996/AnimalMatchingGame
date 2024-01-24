# Animal Matching Game - Readme

## Overview
This animal matching game is an exercise inspired by the Head First C# book series, implemented using MAUI (Microsoft MAUI) in the early release edition for the 2024 version. The game offers an engaging and enjoyable way to practice memory skills while working through the concepts introduced in the book.

## Getting Started
To run the game:

1. Ensure you have the required dependencies installed for MAUI development.
2. Clone or download the project to your local machine.
3. Open the solution in your preferred IDE that supports MAUI development.

## Project Structure
The primary file for the game is `MainPage.xaml.cs`, located in the `AnimalMatchingGame` namespace.

### Code Highlights
- The game initializes with hidden animal buttons using the `AnimalButtons.IsVisible` property.
- When the "Play Again" button is clicked, a randomized set of animal emojis is assigned to the buttons.
- The timer (`TimerTick` method) tracks the elapsed time since the game started.
- Matching logic checks for pairs of clicked buttons with the same emoji, updating the score and revealing the "Play Again" button when all pairs are found.

## How to Play
1. Click on the animal emojis to reveal them.
2. Try to find matching pairs by remembering the emoji positions.
3. Match all pairs to win the game.

## Learning Objective
This game serves as an exercise in applying the concepts learned from the Head First C# book series. The implementation in MAUI provides a practical opportunity to reinforce and practice the principles covered in the book.

## Additional Notes
- The game is designed with simplicity and clarity in mind, making it suitable for players of all ages.
- Colors are used to enhance the visual feedback, indicating selected and matched emojis.

Feel free to explore the code and customize the game further based on your preferences or to align with specific lessons from the Head First C# book series. Have fun playing and learning with the Animal Matching Game!
