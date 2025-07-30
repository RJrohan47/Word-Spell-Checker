# 📝 Spelling Checker using Python

A simple and effective **Spelling Checker** built using Python. It suggests the most probable correct words for a given misspelled input by utilizing basic Natural Language Processing (NLP) techniques, edit distance algorithms, and word frequency probabilities.

---

## 🔍 Overview

This project:

- Reads a large text corpus to calculate word frequencies.
- Implements a correction mechanism based on **edit distance** (1 and 2 edits away).
- Suggests top `n` possible correct words based on their probabilities.
- Uses **Pandas** for displaying suggestions in tabular format.

---

## 🚀 Features

✨ Spelling suggestions for any English word  
✨ Ranked suggestions based on word probability  
✨ Handles common spelling errors like:
  - Insertions
  - Deletions
  - Replacements
  - Transpositions  
✨ Easy-to-understand and modifiable code structure

---

## 🛠️ Tech Stack

| Tool        | Usage                          |
|-------------|--------------------------------|
| `Python`    | Core programming language      |
| `Pandas`    | Tabular output and data structuring |
| `re` (Regex)| Text preprocessing and word extraction |
| `collections.Counter` | Counting word frequency |

---

## 📁 File Structure

Spelling-Checker/
│
├── Spelling checker.ipynb # Main Jupyter notebook with implementation
├── big.txt # Text corpus (used internally if available)
├── README.md # Project documentation (this file)


## 🧑‍💻 Installation & Usage
### 🖥️ Requirements
Python 3.x

Jupyter Notebook

pandas

# Step 1: Clone this repository
git clone https://github.com/yourusername/Spelling-Checker.git
cd Spelling-Checker

# Step 2: Install dependencies
pip install pandas

# Step 3: Open the notebook
jupyter notebook "Spelling checker.ipynb"
