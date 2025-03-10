# Quiz-Game

This project is a simple quiz application implemented in Python. It allows users to answer a series of True/False questions and keeps track of their score. The application is structured into multiple modules for better organization and readability.

Features
Question Bank: A list of True/False questions with their correct answers.

Quiz Logic: Manages the quiz flow, including displaying questions, checking answers, and calculating the score.

Modular Design: The code is divided into separate modules for questions, quiz logic, and data.

How to Use
Run the Program: Execute the main.py script.

Answer Questions: The program will display each question one by one. Answer with "True" or "False".

View Results: After completing the quiz, the program will display your final score.

Code Structure
data.py: Contains the list of questions and their answers.

question_model.py: Defines the Question class to represent a single question.

quiz_brain.py: Implements the QuizBrain class to manage the quiz logic.

main.py: The main script that initializes the quiz and runs it.

Example Usage
plaintext
Copy
0: A slug's blood is green. True/False: True
You got it right
The correct answer was: True
Your current score is: 1/1


1: The loudest animal is the African Elephant. True/False: False
You got it right
The correct answer was: False
Your current score is: 2/2


...

You've completed the quiz
Your final score was: 10/12
