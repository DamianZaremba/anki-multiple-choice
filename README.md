Anki Multiple Choice Template
=============================

Card template for Anki for single-question, multiple-answer (one or more correct) quizzes.

Features:
- Optional image, shown after the question text
- Any number of answers (stored as a JSON `Answers` field: `[{"text": ..., "correct": true|false}, ...]`)
- Front side lets you tick the answers you believe are correct; back side marks each as correct/wrong/missed

# Installation

There are 2 options for installation:

1. Clone this repo and execute scripts/sync-database.py (will update an existing entry)
2. Import the multiple-choice.apkg file from a release
