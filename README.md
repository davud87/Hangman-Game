# Hangman Game – Multi-language Console Application

**Overview**  
This project is a console-based implementation of the classic Hangman word-guessing game, developed in three different programming languages: **C#**, **JavaScript (Node.js)**, and **Python**. The goal is to demonstrate core programming principles and explore language-specific implementations of shared logic.

Players attempt to guess a randomly selected word, either one letter at a time or by submitting the entire word. The game allows a total of six incorrect guesses, after which the game ends. With each incorrect guess, a textual representation of the hangman figure is progressively drawn.

---

**Project Goals**
- Practice algorithmic thinking and control flow in a multi-language context.
- Implement a classic logic-based game using console interfaces.
- Reinforce understanding of input/output handling, string manipulation, and data structures.
- Promote modular and readable code structure across implementations.
- Encourage collaboration through Git and GitHub.

---

**Key Features**
- Console-based gameplay with real-time user interaction.
- Random word selection from a predefined list of 100 words across diverse categories.
- Supports both single-letter and full-word guessing.
- Hangman figure rendered in stages with each incorrect attempt.
- Game status updated live after each guess.
- Unified logic implemented consistently in three languages.
- Designed to be simple, understandable, and beginner-friendly.

---

**Technologies Used**

**C# Version** (`hangmanProject.cs`)
- Language: C#
- Environment: .NET Core / .NET Framework
- Notable features:
  - Encapsulated game logic using static methods
  - LINQ-based character matching (`System.Linq`)
  - Console input/output

**JavaScript Version** (`hangmanProject.js`)
- Language: JavaScript
- Environment: Node.js (v16+)
- Notable features:
  - CLI interaction using `readline` module
  - String/array manipulation
  - Recursive function calls for input loops

**Python Version** (`HangmanProject.py`)
- Language: Python 3
- Environment: Python 3.x
- Notable features:
  - Procedural, function-based structure
  - Enumeration and list-based letter replacement
  - Simple and readable CLI experience

---

**Educational Purpose**  
This project is developed as an academic exercise to deepen the understanding of procedural programming, language syntax differences, and console application development. It provides a comparative view across C#, JavaScript, and Python while reinforcing clean code practices and GitHub-based collaboration.

---

**Authors**
- Imran Mujkanović  
- Adna Ramović  
- Davud Mahmutović
