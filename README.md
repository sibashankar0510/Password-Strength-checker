# Simple Password Strength Checker 🔐

A Python-based command-line tool that evaluates the strength of a password. It checks the password against 5 essential security criteria and provides real-time feedback/suggestions to make it stronger.

## Features
- Evaluates password based on 5 parameters:
  1. Length (at least 8 characters)
  2. Uppercase letters (A-Z)
  3. Lowercase letters (a-z)
  4. Numbers (0-9)
  5. Special characters (e.g., @, #, $, %)
- Calculates a score out of 5.
- Classifies the password as **Weak**, **Medium**, or **Strong**.
- Provides specific suggestions on how to improve a weak/medium password.

## How to Run
1. Make sure you have Python installed on your system.
2. Clone this repository or download the `password_checker.py` file.
3. Open your terminal or command prompt.
4. Run the following command:
   ```bash
   python password_checker.py
