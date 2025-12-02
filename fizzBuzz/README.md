# FizzBuzz in Python

This repository contains a simple Python implementation of the classic **FizzBuzz** programming challenge.  
FizzBuzz is often used as a beginner-friendly exercise to practice conditional statements, loops, and modular arithmetic.

## 📌 How FizzBuzz Works

For any number **n**, the program prints:

- `"FizzBuzz"` → if the number is divisible by **both 3 and 5**
- `"Fizz"` → if the number is divisible by **3 only**
- `"Buzz"` → if the number is divisible by **5 only**
- The number itself → if it is divisible by neither 3 nor 5

## 📂 Code

```python
def fizz_buzz(n):
    for i in range(1, n+1):
        if i % 3 == 0 and i % 5 == 0:
            print("FizzBuzz")
        elif i % 5 == 0:
            print("Buzz")
        elif i % 3 == 0:
            print("Fizz")
        else:
            print(i)

fizz_buzz(10)
# challenges
