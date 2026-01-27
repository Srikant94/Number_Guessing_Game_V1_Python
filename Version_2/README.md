🎯 Number Guessing Game – Version 2 (Python)
📌 Project Overview

The Number Guessing Game (Version 2) is a console-based Python application that challenges the user to guess a randomly generated number within a limited number of attempts.

This version enhances the initial implementation by introducing difficulty levels, dynamic attempt limits, improved scoring logic, and better code structure for readability and scalability.

The project is designed as a learning-focused mini project to strengthen Python fundamentals such as loops, conditionals, functions, exception handling, and user interaction.

🚀 Features

🎚 Multiple Difficulty Levels

Easy

Medium

Hard

🔢 Dynamic Number Range based on selected difficulty

🔄 Dynamic Attempt Limits per difficulty level

🧮 Score Calculation System based on remaining attempts

🔁 Replay Functionality to play multiple rounds

⚠️ Input Validation to handle invalid user input gracefully

🧱 Modular Code Structure using functions

💬 Clear user prompts and feedback messages

🎚 Difficulty Levels Explained
Difficulty	Number Range	Max Attempts
Easy	1 – 10	7
Medium	1 – 20	5
Hard	1 – 30	3

Each difficulty level adjusts the complexity of the game and scoring potential, encouraging smarter guesses.

🧠 Scoring Logic

The score is calculated using the formula:

Score = Remaining Attempts × 15


Higher difficulty levels result in higher risk and reward

If all attempts are exhausted, the score is 0

🛠 Tech Stack

Programming Language: Python

Environment: Jupyter Notebook / Python CLI

Libraries Used:

random (for number generation)

📂 Project Structure
number-guessing-game/
│
├── number_guessing_game_v2.py
├── README.md

▶️ How to Run the Game
1️⃣ Clone the Repository
git clone https://github.com/your-username/number-guessing-game.git

2️⃣ Navigate to the Project Folder
cd number-guessing-game

3️⃣ Run the Game
python number_guessing_game_v2.py


(If using Jupyter Notebook, run the cells sequentially)

🧪 Sample Gameplay Flow

User selects a difficulty level

Game generates a random number within the chosen range

User enters guesses

Game provides hints (Too High / Too Low)

Score is calculated based on remaining attempts

User can choose to replay or exit

🧩 Key Learning Outcomes

This project helped reinforce:

Python functions and modular programming

Loop control and conditional logic

Exception handling using try-except

User input validation

Writing readable and well-commented code

Thinking from a user-experience perspective

🔮 Future Improvements (Planned)

Add a timer-based scoring system

Store high scores using files

Add difficulty-based multipliers

Convert the game into a GUI application

Add automated unit tests

🤝 Contributions

This is a personal learning project, but suggestions and feedback are always welcome.

If you have ideas for improvements, feel free to:

Open an issue

Submit a pull request

Share feedback on LinkedIn

📬 Connect With Me

I’m documenting my journey in Python, Data Science, and AI step by step.

Let’s learn and grow together 🚀

⭐ If you find this project helpful, consider giving it a star!
