# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program

def remove(s):
  
    try:
      
        print("Enter the index of the character to remove:")
        
        n = int(input())
        
        if n < 0 or n >= len(s):
          
            print("Index out of range.")
            
            return s
            
    except ValueError:
      
        print("Invalid input. Please enter a valid number.")
        
        return s

    return s[:n] + s[n+1:]

print("Enter a string:")

string_input = input().strip()


if string_input:
  
    result = remove(string_input)
    
    print("String after removing character at specified index:", result)
    
else:
  
    print("Empty string provided.")

## Output

![Screenshot 2025-04-30 151718](https://github.com/user-attachments/assets/aefc3e45-3baf-429f-9d2f-21951479baa2)


## Result

This program is successfully executed.
