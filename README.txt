# Day 13 - Fibonacci Series in Python

## 📌 Description
This program generates the Fibonacci series for a given number of terms using Python. Each number in the series is the sum of the previous two numbers.

## 💻 Code
```python
n = int(input("Enter number of terms: "))

a, b = 0, 1

for i in range(n):
    print(a, end=" ")
    a, b = b, a + b
```

## ▶️ Example Output
```text
Enter number of terms: 10
0 1 1 2 3 5 8 13 21 34
```

## 🧠 Concepts Learned
- Variables and multiple assignment
- User input using `input()`
- Type conversion using `int()`
- `for` loops and `range()`
- Fibonacci sequence logic

## 🎯 Learning Objective
To understand how to generate a Fibonacci series using loops and variable updates in Python.

## 🚀 Challenge
Modify the program to print the Fibonacci series up to a given maximum value instead of a given number of terms.

---
**100 Days of Python Challenge — Day 13 Completed!** ✅
            