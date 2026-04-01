# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
To write a Python program to demonstrate **Head Recursion** by finding and printing the sequence based on the sum of all digits (even or odd adjusted input).

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `fun(n)`
3. In the function:
   - Create a recursive call at the **beginning** (Head Recursion)
   - Print the result after the recursive call
4. Take input from the user
5. If input is odd, convert it to the next even number
6. Call the recursive function
7. **Stop**

## 💻 PROGRAM:

def sum_of_digits(num): return sum(int(digit) for digit in str(num)) def fun(n): if n <= 0:
return fun(n - 1) print(f"Current value: {n}, Sum of digits: {sum_of_digits(n)}") num =
int(input("Enter a positive integer: ")) if num % 2 != 0: num += 1 print(f"Adjusted input
(even number): {num}\nSequence (head recursion):") fun(num)

## OUTPUT
<img width="772" height="190" alt="image" src="https://github.com/user-attachments/assets/00d04e61-c042-44da-acf6-26021385d5bb" />

## RESULT
Thus, the program has been successfully executed.
