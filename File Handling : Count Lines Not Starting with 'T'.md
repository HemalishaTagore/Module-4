# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
import csv
with open('story.csv', 'w') as f:
    f.write("The sun rises in east\n")
    f.write("Hello guy.\n")
count = 0
with open('story.csv', 'r') as file:
    for line in file:
        if not line.startswith('T'):
            count += 1
print("Lines not starting with 'T':", count)

```

## Output
<img width="417" height="176" alt="Screenshot 2025-10-20 161828" src="https://github.com/user-attachments/assets/54d593d7-14bf-42a3-ace9-7ae921caf86c" />

## Result
Thus, to write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'` is executed successfully.
