# 📐 Taylor Series Using Recursion in Python

## 🎯 AIM:
To write a Python program to evaluate a **Taylor Series** using **recursion**, where values of `x` and `n` are taken from the user.

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `x` and `n`
3. Get values for `x` and `n` from the user
4. Define a recursive function `series(x, n)`
   - **Base case:** If `n == 0`, return 1
   - **Recursive case:** Return `x**n / n + series(x, n-1)`
5. Print the result
6. **Stop**

## 💻 PROGRAM:

def series(x, n):
if n == 0:
return 1
return x**n / n + series(x, n-1)
x, n = 2, 3 # Example inputs
print(series(x, n))
## OUTPUT
<img width="352" height="153" alt="image" src="https://github.com/user-attachments/assets/ea2a07b9-bce5-4d7e-a003-c1aa16724366" />

## RESULT
Thus, the program has been successfully executed.
