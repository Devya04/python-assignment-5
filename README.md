# python-assignment-5
# 📘 Python Programs: Student Records & List Manipulation

This repository includes two beginner-friendly Python programs:

1. **Student Marks Dictionary** – A program that uses a dictionary to store and retrieve student marks.
2. **List Reversal** – A program that demonstrates list slicing and reversing techniques in Python.

---

## ✅ Program 1: Student Marks Dictionary

### 🔧 Problem Statement
Write a Python program that:
1. Creates a dictionary where student names are keys and their marks are values.
2. Asks the user to input a student's name.
3. Retrieves and displays the corresponding marks.
4. If the student’s name is not found, displays an appropriate message.

### 💻 Code:
```python
students = {
    "Alice": 85,
    "Bob": 92,
    "Charlie": 78,
    "Diana": 88,
    "Ethan": 90
}

name = input("Enter the student's name: ")

if name in students:
    print(f"{name}'s marks: {students[name]}")
else:
    print(f"Student '{name}' not found in the records.")

Program 2: List Slicing and Reversing
🔧 Problem Statement
Write a Python program that:

Creates a list of numbers from 1 to 10.

Extracts the first five elements from the list.

Reverses these extracted elements.

Prints both the extracted list and the reversed list.

💻 Code:
numbers = list(range(1, 11))
first_five = numbers[:5]
reversed_five = first_five[::-1]

print("First five elements:", first_five)
print("Reversed list:", reversed_five)
 Explanation of [::-1]:
[::-1] is a slice that reverses the list.

It starts from the end and steps backwards by 1.

This is a clean, Pythonic way to reverse any list.
