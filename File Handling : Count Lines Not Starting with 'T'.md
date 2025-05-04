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
# Step 1: Open the file in read mode
with open('story.txt', 'r') as file:
    count = 0  # Step 2: Initialize the counter

    # Step 3: Iterate through each line
    for line in file:
        # Strip leading spaces and check if line does NOT start with 'T'
        if not line.lstrip().startswith('T'):
            count += 1  # Increment counter if condition is met

# Step 4: Print the result
print("Number of lines not starting with 'T':", count)
```

## Output
![438348206-65ddcf20-e2b7-4282-8e6d-c1fe0421ed04](https://github.com/user-attachments/assets/a421a597-0db2-4255-ae28-b848622e550e)

## Result
Thus the program executed successfully.
