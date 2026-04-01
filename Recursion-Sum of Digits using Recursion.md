# # 🔁 Recursion:Sum of Digits using Recursion in Python

## 🎯 AIM:
To write a Python program to calculate the **sum of all digits** in a number using **recursion**.

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `sum_digit(n)` that:
   - Returns 0 if `n <= 0` (Base Case)
   - Else, returns `n % 10 + sum_digit(n // 10)` (Recursive Case)
3. Take integer input from the user.
4. Call the recursive function and store the result.
5. Print the result.
6. **Stop**

## 💻 PROGRAM:

def sum_digit(n):
return 0 if n <= 0 else n % 10 + sum_digit(n // 10)
n = int(input())
print(sum_digit(n) if n >= 0 else "Enter valid number")
## OUTPUT
<img width="561" height="359" alt="image" src="https://github.com/user-attachments/assets/aef97b56-3658-4b4a-9be8-7ebb09cf735c" />

## RESULT
Thus, the program has been successfully executed.
