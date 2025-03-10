# AI-Based Number Guessing Game

## Overview
This is an AI-powered number guessing game built in Python. The AI uses a combination of logical guessing and probabilistic estimation to guess the number chosen by the user. The game provides feedback on whether the guessed number is too high or too low, allowing the AI to refine its predictions.

## Features
- AI intelligently guesses the number using a binary search or machine learning model.
- User selects a secret number within a specified range.
- AI receives feedback and optimizes its guesses.
- Simple and interactive command-line interface.

## Requirements
Ensure you have Python installed. You can install the required dependencies using:

```bash
pip install -r requirements.txt
```

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/ai-number-guessing-game.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ai-number-guessing-game
   ```
3. Run the game:
   ```bash
   python game.py
   ```

## How It Works
1. The user thinks of a number within a specified range.
2. The AI makes a guess and waits for feedback:
   - **Too high**
   - **Too low**
   - **Correct**
3. The AI adjusts its guess accordingly until it finds the correct number.

## AI Logic
The AI utilizes:
- **Binary Search**: If the range is known, AI uses binary search to guess efficiently.
- **Machine Learning (Optional)**: Advanced implementation can use reinforcement learning techniques to predict numbers based on user behavior.

## License
This project is licensed under the **MIT License**.



