# 🐍 Python Challenge #2: Count Words in a Sentence

This repository contains a **reference implementation** for **Python Challenge #2** from  
👉 **SolveWithPython.com**

This challenge focuses on **string parsing**, **whitespace handling**, and **defensive input logic** in Python.

---

## 📌 Challenge Description

Write a Python function that counts the number of words in a given sentence.

### Requirements
- The function must accept a string as input
- It must return an integer representing the word count
- A word is defined as any sequence of characters separated by whitespace
- The function should handle:
  - Extra spaces between words
  - Leading and trailing spaces
  - Empty strings

---

## 🧠 Example

```python
count_words("Hello world")
# Output: 2

count_words("  This   has   extra spaces ")
# Output: 4

count_words("")
# Output: 0



