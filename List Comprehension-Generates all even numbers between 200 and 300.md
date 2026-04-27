# 🧾 List Comprehension:Generates all even numbers between 200 and 300
## 🎯 AIM:
To write a Python class-based program that generates all even numbers between 200 and 300 using **list comprehension**, and stores them in a list.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a class named `program`
3. Create variables `a`, `b`, and `c` to represent:
   - `a`: Lower limit
   - `b`: Step value
   - `c`: Upper limit
4. Initialize the values using a constructor `__init__`
5. Define a method `display()` that uses **list comprehension** to store even numbers
6. Print the resulting list of even numbers
7. **Stop**

---

## 💻 PROGRAM:
```py

class Program:
    def __init__(self, a, b, c):
        self.a, self.b, self.c = a, b, c

    def display(self):
        return [i for i in range(self.a, self.c + 1, self.b)]

print(Program(200, 2, 301).display())
```
## OUTPUT:

<img width="1132" height="192" alt="447875869-7c2a01d9-d4d5-4d4c-b90c-d6d251e63d1e" src="https://github.com/user-attachments/assets/cca2d96c-38ec-4f59-870e-14c1068f41ec" />

## RESULT:
Thus, the program has been successfully executed.
