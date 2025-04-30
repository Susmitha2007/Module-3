# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program

import re

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

filtered_words = [word for word in items if not re.search(r'e', word)]

print("Words without 'e':", filtered_words)

## Output

![Screenshot 2025-04-30 150627](https://github.com/user-attachments/assets/42f5aa8f-097a-416f-b783-53d5d5db837e)


## Result

This program is successfully executed.
