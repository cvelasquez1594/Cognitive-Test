# 🧠 Cognitive Ability Game

This is a Python-based cognitive quiz game with a graphical user interface built using `tkinter`. It uses a decision-tree structure defined in a JSON file to guide the user through a series of questions and score them based on their responses.

## 📋 Features

- Interactive GUI built with `tkinter`
- Decision-tree-based question flow (via nested JSON)
- Tracks user score dynamically
- Final results screen with "Play Again" option
- Clean, responsive button layout
- Simple and customizable JSON-based question/answer system

## 📁 Project Structure

├── cognitive_game.py # Main game script
├── questions.json # JSON file defining the question tree and logic


## 📦 Requirements

- Python 3.x
- `tkinter` (included with most Python installations)

## 🛠 How It Works

1. The game loads a decision tree from `questions.json`
2. Each question contains:
   - A `"question"` string
   - An `"answers"` dictionary mapping choices to the next question or a final result
   - A `"scores"` dictionary assigning a score to each answer
3. The GUI dynamically displays the current question and updates the UI based on user input
4. When the tree reaches a leaf node, a final message and the user's score are shown

## 🚀 Running the Game

Make sure Python is installed, then run:

```bash
python cognitive_game.py

