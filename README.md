# 🎯 Python Quiz Game

<p align="center">
  An interactive command-line quiz application built with Python that tests knowledge through multiple-choice questions and provides instant scoring feedback.
</p>

---

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Project Type](https://img.shields.io/badge/Project-CLI%20Application-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

</p>

---

# 📌 Overview

**Python Quiz Game** is an interactive command-line application designed to demonstrate how fundamental Python concepts can be combined to create a complete working program.

The application presents users with a series of multiple-choice questions, collects user responses, verifies answers, calculates the final score, and provides performance feedback.

This project focuses on developing strong programming fundamentals through practical implementation rather than isolated exercises.

---

# 🎯 Project Objectives

The main objectives of this project are:

- Build an interactive Python application
- Practice organizing structured information
- Improve logical thinking and problem-solving skills
- Understand program flow and user interaction
- Apply Python fundamentals in a real project environment
- Develop cleaner and more maintainable code

---

# ✨ Key Features

## 📝 Multiple Choice Question System

The game provides:

- A collection of questions
- Four answer choices for each question
- User answer input
- Automatic answer verification

---

## ✅ Answer Checking System

The program compares the player's answer with the correct answer and immediately displays the result.

Example:

```
User Answer: D

Result:
✅ Correct!
```

or

```
User Answer: A

Result:
❌ Incorrect!
Correct Answer: C
```

---

## 📊 Automatic Score Calculation

The application calculates the final performance percentage:

Example:

```
Total Questions: 10
Correct Answers: 8

Final Score: 80%
```

---

## 🏆 Performance Feedback

The program provides different messages depending on the final score:

```
100%  → Perfect Score
70%+  → Great Job
50%+  → Good Effort
Below → Keep Practicing
```

---

# 🏗️ Application Workflow

The program follows this execution process:

```
                 Start Program
                       |
                       ↓
              Load Questions
                       |
                       ↓
              Display Question
                       |
                       ↓
              Show Answer Options
                       |
                       ↓
              Receive User Input
                       |
                       ↓
              Check Answer
                       |
                       ↓
              Update Score
                       |
                       ↓
              Display Final Result
```

---

# 🧠 Python Concepts Implemented

## 📦 Tuples

Tuples are used to store fixed information such as:

- Quiz questions
- Answer options
- Correct answers

Example:

```python
questions = (
    "Question 1",
    "Question 2"
)
```

---

## 📋 Lists

Lists are used to store changing information such as user answers.

Example:

```python
guesses = []
```

---

## 🔁 Loops

Loops allow the program to repeat actions efficiently.

Used for:

- Displaying questions
- Showing options
- Processing answers

Example:

```python
for question in questions:
    print(question)
```

---

## 🔀 Conditional Logic

Conditional statements are used to compare answers.

Example:

```python
if guess == answer:
    score += 1
```

---

## ⌨️ User Input Handling

The program interacts with the player through keyboard input.

Example:

```python
input("Enter your answer:")
```

---

# 📂 Project Structure

```
python-quiz-game-v1/

│
├── quiz_game.py        # Main application file
│
├── README.md           # Project documentation
│
└── LICENSE             # License information
```

---

# ⚙️ Requirements

Before running this project, make sure you have:

- Python 3.x installed
- A code editor (VS Code recommended)

No external libraries are required.

---

# 🚀 Installation & Running

## Clone Repository

```bash
git clone https://github.com/your-username/python-quiz-game-v1.git
```

---

## Open Project Folder

```bash
cd python-quiz-game-v1
```

---

## Run Application

```bash
python quiz_game.py
```

---

# 🖥️ Example Gameplay

```
---------------------------
Question 1

What is the capital city of Spain?

A. London
B. Paris
C. Rome
D. Madrid

Enter your answer: D

✅ CORRECT!
```

Final result:

```
===========================
        FINAL RESULTS
===========================

Correct Answers:
D C C B B C C B C B

Your Score: 90%

🔥 Great Job!
```

---

# 🔮 Future Development Roadmap

## Version 2.0

Planned improvements:

- Add more quiz categories
- Add difficulty levels
- Randomize questions
- Add a timer system

---

## Version 3.0

Advanced features:

- Save player scores
- Create a leaderboard
- Add user profiles
- Store questions in external files

---

## Version 4.0

Application upgrade:

- Build a graphical user interface
- Add animations
- Create a complete quiz platform

---

# 📈 Learning Progress

This project represents the transition from practicing individual Python concepts to building complete applications.

```
Python Basics
      ↓
Variables & Data Types
      ↓
Conditions
      ↓
Loops
      ↓
Collections
      ↓
User Input
      ↓
Application Development
```

---

# 🛠️ Skills Developed

Through this project, I improved:

- Python programming fundamentals
- Logical problem solving
- Code organization
- Debugging skills
- Data management
- Application design thinking

---

# 👨‍💻 Author

## Muhammad Raheel Babar

A Python learner building practical projects to strengthen programming skills and explore future areas including software development, artificial intelligence, cybersecurity, and advanced computing.

This repository represents continuous improvement through consistent practice and project-based learning.

---

# ⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub.

Building projects is how programming skills grow — one improvement at a time. 🚀
