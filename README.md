# Apple Pie - iOS Game

## Overview

**Apple Pie** is a fun and interactive iOS game developed to practice core iOS development concepts using **UIKit** and **Swift**. This project showcases how to build an engaging user interface, handle user input, and manage basic game logic with Swift.

In **Apple Pie**, users can play a simple game involving guessing letters to reveal an apple pie recipe. The game offers a great opportunity to get hands-on experience with user interface elements like buttons, labels, and text fields in a real app environment.

---

## Features

- **Simple User Interface**: The app includes UI components like buttons, labels, and images to create an intuitive and engaging experience.
- **Interactive Gameplay**: Users are given a word to guess, and they can select letters to fill in the blanks. Each wrong guess reduces the number of attempts.
- **Real-time Updates**: The UI dynamically updates based on the user's input, displaying the progress of the game and remaining attempts.
- **Basic Animations**: As the player makes guesses, animations and visual feedback help keep the game interactive and engaging.

---

## Key Learnings

### UIKit and Views
This project involves using UIKit, Apple's framework for building iOS applications. Key components used in the project include:
- **UILabels** to display the word being guessed and the number of remaining attempts.
- **UIButton** for the user to select letters.
- **UIImageView** to show visual feedback for correct or incorrect guesses.

### User Input and Event Handling
The app responds to user interactions using **actions and outlets** in Swift. Buttons are linked to actions that process the player's guesses, while labels and other views are updated based on the user's progress.

### Game Logic
The core logic of the game involves:
- Displaying a word with blanks for each letter.
- Checking if the guessed letter is part of the word.
- Updating the game state and UI after each guess.

---

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/apple-pie.git
