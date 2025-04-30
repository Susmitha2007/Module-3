# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program

original_string = "google"

reversed_string = original_string[::-1]

if original_string == reversed_string:

    print(f'"{original_string}" is a palindrome.')
    
else:

    print(f'"{original_string}" is not a palindrome.')

## Output

![Screenshot 2025-04-30 152205](https://github.com/user-attachments/assets/cd81b343-3246-432d-a116-b4469a3956f3)


## Result

This program is successfully executed.
